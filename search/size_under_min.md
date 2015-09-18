# set size

*Generated: Fri Sep 18 2015 15:38:44 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&size=0"
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
  "content-length": "706",
  "etag": "W/\"2c2-f6cu4sGQgxc2w7NCde171g\"",
  "date": "Fri, 18 Sep 2015 13:38:43 GMT",
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
      "size": 1,
      "private": false
    },
    "warnings": [
      "out-of-range integer 'size', using MIN_SIZE"
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583523973
  },
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "id": "3374:adm1:es:esp:a_coru_a",
        "layer": "region",
        "source": "qs",
        "name": "A Coruña",
        "country_a": "ESP",
        "country": "Spain",
        "region": "A Coruña",
        "confidence": 0.54,
        "label": "A Coruña"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -8.46415604849368,
          43.1260515324895
        ]
      }
    }
  ],
  "bbox": [
    -8.46415604849368,
    43.1260515324895,
    -8.46415604849368,
    43.1260515324895
  ]
}
```

## Tests

### ✓ expected warnings
```javascript
should.exist json.geocoding.warnings
json.geocoding.warnings.should.eql [ 'out-of-range integer \'size\', using MIN_SIZE' ]
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

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
```

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
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

