# bounding country

*Generated: Fri Sep 18 2015 15:39:01 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=1&point.lon=1&boundary.country=ZZZ"
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
  "content-length": "382",
  "etag": "W/\"17e-+kb8T6nKnUojgZgZqmwutA\"",
  "date": "Fri, 18 Sep 2015 13:39:01 GMT",
  "connection": "close"
}
```
```javascript
{
  "geocoding": {
    "version": "0.1",
    "attribution": "http://pelias.mapzen.com/v1/attribution",
    "query": {
      "size": 10,
      "private": false,
      "point.lat": 1,
      "point.lon": 1,
      "boundary.circle.lat": 1,
      "boundary.circle.lon": 1
    },
    "errors": [
      "ZZZ is not a valid ISO2/ISO3 country code"
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583541166
  },
  "type": "FeatureCollection",
  "features": []
}
```

## Tests

### ✓ 200 ok
```javascript
response.statusCode.should.be.equal 200
response.should.have.header 'charset', 'utf8'
response.should.have.header 'content-type', 'application/json; charset=utf-8'
```

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

### ✓ expected errors
```javascript
should.exist json.geocoding.errors
json.geocoding.errors.should.eql [ 'ZZZ is not a valid ISO2/ISO3 country code' ]
```

### ✓ inputs
```javascript
json.geocoding.query['size'].should.eql 10
should.not.exist json.geocoding.query['boundary.country']
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

