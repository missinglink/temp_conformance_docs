# sources filter

*Generated: Fri Sep 18 2015 15:38:52 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&sources=openstreetmap"
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
  "content-length": "471",
  "etag": "W/\"1d7-hlful/clek4o+bqaK7+nyg\"",
  "date": "Fri, 18 Sep 2015 13:38:51 GMT",
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
        "from_sources": [
          "osmaddress",
          "osmnode",
          "osmway"
        ]
      },
      "size": 10,
      "private": false,
      "type": [
        "osmaddress",
        "osmnode",
        "osmway"
      ]
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583531973
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

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
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

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
json.geocoding.query.types['from_sources'].should.eql ["osmaddress","osmnode","osmway"]
json.geocoding.query['type'].should.eql ["osmaddress","osmnode","osmway"]
```

