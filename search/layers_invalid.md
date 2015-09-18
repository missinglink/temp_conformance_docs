# layer alias

*Generated: Fri Sep 18 2015 15:38:40 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&layers=notlayer"
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
  "content-length": "427",
  "etag": "W/\"1ab-h4Do8nUYM7Ga+6NOqeO5RA\"",
  "date": "Fri, 18 Sep 2015 13:38:38 GMT",
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
      "size": 10,
      "private": false
    },
    "errors": [
      "'notlayer' is an invalid layers parameter. Valid options: venue,address,country,region,county,locality,localadmin,neighbourhood,coarse"
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583518536
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

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
should.not.exist json.geocoding.query['types']
should.not.exist json.geocoding.query['type']
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
json.geocoding.errors.should.eql [ '\'notlayer\' is an invalid layers parameter. Valid options: venue,address,country,region,county,locality,localadmin,neighbourhood,coarse' ]
```

### ✓ 200 ok
```javascript
response.statusCode.should.be.equal 200
response.should.have.header 'charset', 'utf8'
response.should.have.header 'content-type', 'application/json; charset=utf-8'
```

