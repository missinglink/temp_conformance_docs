# focus point null island

*Generated: Fri Sep 18 2015 15:38:38 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&focus.point.lat=0&focus.point.lon=0"
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
  "content-length": "3749",
  "etag": "W/\"ea5-orpCr0leXzU0lDKk8BGApA\"",
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
      "focus.point.lat": 0,
      "focus.point.lon": 0
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583516389
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
        "confidence": 0.8809860896023863,
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
        "confidence": 0.6760565624813237,
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
        "confidence": 0.673309857946705,
        "label": "Gustavo A. Madero, Distrito Federal"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -99.1158597142034,
          19.5040687748969
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "6509:adm2:de:deu:muehldorf_a__inn",
        "layer": "county",
        "source": "qs",
        "name": "Muehldorf A. Inn",
        "country_a": "DEU",
        "country": "Germany",
        "region": "Bayern",
        "county": "Muehldorf A. Inn",
        "confidence": 0.673309857946705,
        "label": "Muehldorf A. Inn, Bayern"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          12.3818094943376,
          48.2393018867677
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "11173:adm2:mx:mex:general_canuto_a__neri",
        "layer": "county",
        "source": "qs",
        "name": "General Canuto A. Neri",
        "country_a": "MEX",
        "country": "Mexico",
        "region": "Guerrero",
        "county": "General Canuto A. Neri",
        "confidence": 0.673309857946705,
        "label": "General Canuto A. Neri, Guerrero"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -100.104177508501,
          18.4411264675917
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "982:adm1:hn:hnd:gracias_a_dios",
        "layer": "region",
        "source": "qs",
        "name": "Gracias A Dios",
        "country_a": "HND",
        "country": "Honduras",
        "region": "Gracias A Dios",
        "confidence": 0.673309857946705,
        "label": "Gracias A Dios"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -84.3596374442632,
          15.2312424482025
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "275:adm0:au:aus:_",
        "layer": "country",
        "source": "qs",
        "name": "Australia",
        "country_a": "AUS",
        "country": "Australia",
        "confidence": 0.6499294790323675,
        "label": "Australia"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          134.490286361248,
          -25.7283995507395
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "4651:adm1:us:usa:arizona",
        "layer": "region",
        "source": "qs",
        "name": "Arizona",
        "country_a": "USA",
        "country": "United States",
        "region": "Arizona",
        "confidence": 0.6499294790323675,
        "label": "Arizona"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -111.664391671618,
          34.293065090554
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "3263:adm1:ca:can:alberta",
        "layer": "region",
        "source": "qs",
        "name": "Alberta",
        "country_a": "CAN",
        "country": "Canada",
        "region": "Alberta",
        "confidence": 0.6499294790323675,
        "label": "Alberta"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -114.513161746572,
          55.1681285938626
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "154:adm0:ar:arg:_",
        "layer": "country",
        "source": "qs",
        "name": "Argentina",
        "country_a": "ARG",
        "country": "Argentina",
        "confidence": 0.6499294790323675,
        "label": "Argentina"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -65.1673660041751,
          -35.3864080843045
        ]
      }
    }
  ],
  "bbox": [
    -114.513161746572,
    -35.3864080843045,
    134.490286361248,
    55.1681285938626
  ]
}
```

## Tests

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
json.geocoding.query['focus.point.lat'].should.eql 0
json.geocoding.query['focus.point.lon'].should.eql 0
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
should.not.exist json.geocoding.warnings
```

