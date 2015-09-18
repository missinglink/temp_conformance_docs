# set size

*Generated: Fri Sep 18 2015 15:38:59 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=1&point.lon=1&size=0"
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
  "content-length": "749",
  "etag": "W/\"2ed-A9A/HOdL/VWLRTWbksv6qw\"",
  "date": "Fri, 18 Sep 2015 13:38:57 GMT",
  "connection": "close"
}
```
```javascript
{
  "geocoding": {
    "version": "0.1",
    "attribution": "http://pelias.mapzen.com/v1/attribution",
    "query": {
      "size": 1,
      "private": false,
      "point.lat": 1,
      "point.lon": 1,
      "boundary.circle.lat": 1,
      "boundary.circle.lon": 1
    },
    "warnings": [
      "out-of-range integer 'size', using MIN_SIZE"
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583537828
  },
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "id": "375:_:_:gha:ridge",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Ridge",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Greater Accra",
        "label": "Ridge, Greater Accra"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -0.216653655604662,
          5.54358390711829
        ]
      }
    }
  ],
  "bbox": [
    -0.216653655604662,
    5.54358390711829,
    -0.216653655604662,
    5.54358390711829
  ]
}
```

## Tests

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

### ✓ inputs
```javascript
json.geocoding.query['size'].should.eql 1
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

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
```

### ✓ expected warnings
```javascript
should.exist json.geocoding.warnings
json.geocoding.warnings.should.eql [ 'out-of-range integer \'size\', using MIN_SIZE' ]
```

