# sources and layers specified (invalid combo)

*Generated: Fri Sep 18 2015 15:38:45 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&sources=quattroshapes&layers=address"
}
```

## Response
```javascript
Status: 200
{
  "x-powered-by": "mapzen",
  "charset": "utf8",
  "cache-control": "public,max-age=60",
  "server": "Pelias/2.2.0",
  "access-control-allow-origin": "*",
  "access-control-allow-methods": "GET, OPTIONS",
  "access-control-allow-headers": "X-Requested-With,content-type",
  "access-control-allow-credentials": "true",
  "content-type": "application/json; charset=utf-8",
  "content-length": "631",
  "etag": "W/\"277-qd7+RO9ejFoe8/xzQqY5vw\"",
  "date": "Fri, 18 Sep 2015 13:38:45 GMT",
  "connection": "close"
}
```
```javascript
{
  "geocoding": {
    "version": "0.1",
    "attribution": "http://pelias.mapzen.com/v1/attribution",
    "query": {
      "text": "a",
      "parsed_text": {},
      "types": {
        "from_address_parsing": [
          "admin0",
          "admin1",
          "admin2",
          "neighborhood",
          "locality",
          "local_admin"
        ],
        "from_layers": [
          "osmaddress",
          "openaddresses"
        ],
        "from_sources": [
          "admin0",
          "admin1",
          "admin2",
          "neighborhood",
          "locality",
          "local_admin"
        ]
      },
      "size": 10,
      "private": false
    },
    "errors": [
      "You have specified both the `sources` and `layers` parameters in a combination that will return no results."
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583525146
  },
  "type": "FeatureCollection",
  "features": []
}
```

## Tests

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

### ✓ 200 ok
```javascript
response.statusCode.should.be.equal 200
response.should.have.header 'charset', 'utf8'
response.should.have.header 'content-type', 'application/json; charset=utf-8'
```

### ✓ valid geocoding block
```javascript
should.exist json.geocoding
should.exist json.geocoding.version
should.exist json.geocoding.attribution
should.exist json.geocoding.query
should.exist json.geocoding.engine
should.exist json.geocoding.engine.name
should.exist json.geocoding.engine.author
should.exist json.geocoding.engine.version
should.exist json.geocoding.timestamp
```

### ✓ expected errors
```javascript
should.exist json.geocoding.errors
json.geocoding.errors.should.eql [ 'You have specified both the `sources` and `layers` parameters in a combination that will return no results.' ]
```

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
json.geocoding.query.types['from_layers'].should.eql ["osmaddress","openaddresses"]
json.geocoding.query.types['from_sources'].should.eql ["admin0","admin1","admin2","neighborhood","locality","local_admin"]
should.not.exist json.geocoding.query['type']
```

