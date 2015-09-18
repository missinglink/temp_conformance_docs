# point

*Generated: Fri Sep 18 2015 15:39:13 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lon=-73.990342"
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
  "content-length": "335",
  "etag": "W/\"14f-7u+h5Ww2JRaCtkPArZpuAw\"",
  "date": "Fri, 18 Sep 2015 13:39:09 GMT",
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
      "private": false
    },
    "errors": [
      "missing point param 'point' requires all of: 'lat','lon' to be present"
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583549161
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

### ✓ expected errors
```javascript
should.exist json.geocoding.errors
json.geocoding.errors.should.eql [ 'missing point param \'point\' requires all of: \'lat\',\'lon\' to be present' ]
```

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

### ✓ inputs
```javascript
json.geocoding.query['size'].should.eql 10
should.not.exist json.geocoding.query['point.lat']
should.not.exist json.geocoding.query['point.lon']
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

### ✓ 200 ok
```javascript
response.statusCode.should.be.equal 200
response.should.have.header 'charset', 'utf8'
response.should.have.header 'content-type', 'application/json; charset=utf-8'
```

