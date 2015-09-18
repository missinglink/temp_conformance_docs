# bounding circle

*Generated: Fri Sep 18 2015 15:38:57 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=40.744243&point.lon=-73.990342&boundary.circle.radius=foo"
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
  "content-length": "413",
  "etag": "W/\"19d-lqH4Ijyemq7984Oeu/iwWw\"",
  "date": "Fri, 18 Sep 2015 13:38:56 GMT",
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
      "point.lat": 40.744243,
      "point.lon": -73.990342,
      "boundary.circle.lat": 40.744243,
      "boundary.circle.lon": -73.990342
    },
    "errors": [
      "missing param 'boundary.circle.radius'"
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583536519
  },
  "type": "FeatureCollection",
  "features": []
}
```

## Tests

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

### ✓ expected errors
```javascript
should.exist json.geocoding.errors
json.geocoding.errors.should.eql [ 'missing param \'boundary.circle.radius\'' ]
```

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
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
json.geocoding.query['size'].should.eql 10
json.geocoding.query['point.lat'].should.eql 40.744243
json.geocoding.query['point.lon'].should.eql -73.990342
json.geocoding.query['boundary.circle.lat'].should.eql 40.744243
json.geocoding.query['boundary.circle.lon'].should.eql -73.990342
should.not.exist json.geocoding.query['boundary.circle.radius']
```

