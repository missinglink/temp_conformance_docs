# address parsing

*Generated: Fri Sep 18 2015 15:38:33 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=30%20w%2026th%20st%2C%20ny"
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
  "content-length": "4086",
  "etag": "W/\"ff6-edP4L6NarOjTR+1BIqkZ5g\"",
  "date": "Fri, 18 Sep 2015 13:38:33 GMT",
  "connection": "close"
}
```
```javascript
{
  "geocoding": {
    "version": "0.1",
    "attribution": "http://pelias.mapzen.com/v1/attribution",
    "query": {
      "text": "30 w 26th st, ny",
      "parsed_text": {
        "name": "30 w 26th st",
        "number": 30,
        "street": "w 26th st",
        "state": "NY",
        "regions": [],
        "admin_parts": "ny"
      },
      "size": 10,
      "private": false
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583513368
  },
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "id": "26895:_:_:usa:26th_street_ardmore",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "26th Street/ardmore",
        "country_a": "USA",
        "country": "United States",
        "region": "Georgia",
        "county": "Fulton",
        "confidence": 0.5,
        "label": "26th Street/ardmore, Fulton, Georgia"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -84.3912339703019,
          33.8109318922094
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "28842:_:_:usa:north_26th_street",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "North 26th Street",
        "country_a": "USA",
        "country": "United States",
        "region": "Colorado",
        "county": "Boulder",
        "confidence": 0.5,
        "label": "North 26th Street, Boulder, Colorado"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -105.263022787047,
          40.0457287643513
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "12213:adm2:mx:mex:san_juan_mixtepec__dto__26__",
        "layer": "county",
        "source": "qs",
        "name": "San Juan Mixtepec -dto. 26 -",
        "country_a": "MEX",
        "country": "Mexico",
        "region": "Oaxaca",
        "county": "San Juan Mixtepec -dto. 26 -",
        "confidence": 0.5,
        "label": "San Juan Mixtepec -dto. 26 -, Oaxaca"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -96.3131793895566,
          16.2466940211791
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "12215:adm2:mx:mex:san_pedro_mixtepec__dto__26__",
        "layer": "county",
        "source": "qs",
        "name": "San Pedro Mixtepec -dto. 26 -",
        "country_a": "MEX",
        "country": "Mexico",
        "region": "Oaxaca",
        "county": "San Pedro Mixtepec -dto. 26 -",
        "confidence": 0.5,
        "label": "San Pedro Mixtepec -dto. 26 -, Oaxaca"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -96.2095787389108,
          16.2187837163827
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "6603:adm2:de:deu:st__wendel",
        "layer": "county",
        "source": "qs",
        "name": "St. Wendel",
        "country_a": "DEU",
        "country": "Germany",
        "region": "Saarland",
        "county": "St. Wendel",
        "confidence": 0.5,
        "label": "St. Wendel, Saarland"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          7.10041764378803,
          49.5195837902218
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "12091:adm2:mx:mex:san_pedro_mixtepec__dto__22__",
        "layer": "county",
        "source": "qs",
        "name": "San Pedro Mixtepec -dto. 22 -",
        "country_a": "MEX",
        "country": "Mexico",
        "region": "Oaxaca",
        "county": "San Pedro Mixtepec -dto. 22 -",
        "confidence": 0.5,
        "label": "San Pedro Mixtepec -dto. 22 -, Oaxaca"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -97.0695786862049,
          15.9496452975421
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "31998:locality:ca:can:st__philips_no__301",
        "layer": "locality",
        "source": "qs",
        "name": "St. Philips No. 301",
        "country_a": "CAN",
        "country": "Canada",
        "region": "Saskatchewan",
        "confidence": 0.5,
        "label": "St. Philips No. 301, Saskatchewan"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -101.81364705453,
          51.7901312462152
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "34699:locality:ca:can:st__philips_no__301",
        "layer": "locality",
        "source": "qs",
        "name": "St. Philips No. 301",
        "country_a": "CAN",
        "country": "Canada",
        "region": "Saskatchewan",
        "confidence": 0.5,
        "label": "St. Philips No. 301, Saskatchewan"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -101.81364705453,
          51.7901312462152
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "13918:adm2:pl:pol:m__st__warszawa",
        "layer": "county",
        "source": "qs",
        "name": "M. St. Warszawa",
        "country_a": "POL",
        "country": "Poland",
        "region": "Mazowieckie",
        "county": "M. St. Warszawa",
        "confidence": 0.5,
        "label": "M. St. Warszawa, Mazowieckie"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          21.0477347041736,
          52.2293437694735
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "3787:adm1:gb:gbr:west_sussex",
        "layer": "region",
        "source": "qs",
        "name": "West Sussex",
        "country_a": "GBR",
        "country": "United Kingdom",
        "region": "West Sussex",
        "confidence": 0.5,
        "label": "West Sussex, United Kingdom"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -0.494878637716959,
          50.9555327175587
        ]
      }
    }
  ],
  "bbox": [
    -105.263022787047,
    15.9496452975421,
    21.0477347041736,
    52.2293437694735
  ]
}
```

## Tests

### ✓ address parsing
```javascript
json.geocoding.query.parsed_text['name'].should.eql '30 w 26th st'
json.geocoding.query.parsed_text['number'].should.eql 30
json.geocoding.query.parsed_text['street'].should.eql 'w 26th st'
json.geocoding.query.parsed_text['state'].should.eql 'NY'
json.geocoding.query.parsed_text['regions'].should.eql []
json.geocoding.query.parsed_text['admin_parts'].should.eql "ny"
```

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql '30 w 26th st, ny'
json.geocoding.query['size'].should.eql 10
```

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
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

