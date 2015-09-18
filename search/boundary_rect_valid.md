# bounding rectangle

*Generated: Fri Sep 18 2015 15:38:39 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&boundary.rect.min_lat=-40.659&boundary.rect.max_lat=-41.614&boundary.rect.min_lon=174.612&boundary.rect.max_lon=176.333"
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
  "content-length": "407",
  "etag": "W/\"197-+IQYsmqUhIQEXwiKpgkUsw\"",
  "date": "Fri, 18 Sep 2015 13:38:36 GMT",
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
      "private": false,
      "boundary.rect.min_lat": -40.659,
      "boundary.rect.max_lat": -41.614,
      "boundary.rect.min_lon": 174.612,
      "boundary.rect.max_lon": 176.333
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583516660
  },
  "type": "FeatureCollection",
  "features": []
}
```

## Tests

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
```

### ✓ 200 ok
```javascript
response.statusCode.should.be.equal 200
response.should.have.header 'charset', 'utf8'
response.should.have.header 'content-type', 'application/json; charset=utf-8'
```

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
json.geocoding.query['boundary.rect.min_lat'].should.eql -40.659
json.geocoding.query['boundary.rect.max_lat'].should.eql -41.614
json.geocoding.query['boundary.rect.min_lon'].should.eql 174.612
json.geocoding.query['boundary.rect.max_lon'].should.eql 176.333
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

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

