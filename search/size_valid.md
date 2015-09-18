# set size

*Generated: Fri Sep 18 2015 15:38:47 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&size=3"
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
  "content-length": "1466",
  "etag": "W/\"5ba-19VeLK6mXHIC4wbqSQOC/A\"",
  "date": "Fri, 18 Sep 2015 13:38:44 GMT",
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
      "size": 3,
      "private": false
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583524977
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
        "confidence": 0.8815390227547176,
        "label": "A Coruña"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -8.46415604849368,
          43.1260515324895
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "12977:adm2:mx:mex:carlos_a__carrillo",
        "layer": "county",
        "source": "qs",
        "name": "Carlos A. Carrillo",
        "country_a": "MEX",
        "country": "Mexico",
        "region": "Veracruz De Ignacio De La Llave",
        "county": "Carlos A. Carrillo",
        "confidence": 0.6621360917101049,
        "label": "Carlos A. Carrillo, Veracruz De Ignacio De La Llave"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -95.718942406406,
          18.3270210607444
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "11159:adm2:mx:mex:gustavo_a__madero",
        "layer": "county",
        "source": "qs",
        "name": "Gustavo A. Madero",
        "country_a": "MEX",
        "country": "Mexico",
        "region": "Distrito Federal",
        "county": "Gustavo A. Madero",
        "confidence": 0.6513248855351774,
        "label": "Gustavo A. Madero, Distrito Federal"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -99.1158597142034,
          19.5040687748969
        ]
      }
    }
  ],
  "bbox": [
    -99.1158597142034,
    18.3270210607444,
    -8.46415604849368,
    43.1260515324895
  ]
}
```

## Tests

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 3
```

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
should.not.exist json.geocoding.errors
```

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

