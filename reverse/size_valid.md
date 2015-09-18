# set size

*Generated: Fri Sep 18 2015 15:39:12 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=1&point.lon=1&size=3"
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
  "content-length": "1300",
  "etag": "W/\"514-U2iMOkEJsLsTXAV0Hfgn0A\"",
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
      "size": 3,
      "private": false,
      "point.lat": 1,
      "point.lon": 1,
      "boundary.circle.lat": 1,
      "boundary.circle.lon": 1
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583549204
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
    },
    {
      "type": "Feature",
      "properties": {
        "id": "373:_:_:gha:christiansborg",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Christiansborg",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Greater Accra",
        "label": "Christiansborg, Greater Accra"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -0.174740406126871,
          5.55772347540766
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "372:_:_:gha:burma_camp",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Burma Camp",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Greater Accra",
        "label": "Burma Camp, Greater Accra"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -0.144206298834891,
          5.58942022340274
        ]
      }
    }
  ],
  "bbox": [
    -0.216653655604662,
    5.54358390711829,
    -0.144206298834891,
    5.58942022340274
  ]
}
```

## Tests

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
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

### ✓ 200 ok
```javascript
response.statusCode.should.be.equal 200
response.should.have.header 'charset', 'utf8'
response.should.have.header 'content-type', 'application/json; charset=utf-8'
```

### ✓ inputs
```javascript
json.geocoding.query['size'].should.eql 3
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

