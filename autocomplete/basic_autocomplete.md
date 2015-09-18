# basic autocomplete

*Generated: Fri Sep 18 2015 15:39:12 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/autocomplete?text=a"
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
  "content-length": "3960",
  "etag": "W/\"f78-fdUNs9Vwl2IrxCJIKCNKtg\"",
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
      "text": "a",
      "parsed_text": {},
      "size": 10,
      "private": false
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583549146
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
        "confidence": 0.8819031980500048,
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
        "confidence": 0.6761650455704701,
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
        "id": "6509:adm2:de:deu:muehldorf_a__inn",
        "layer": "county",
        "source": "qs",
        "name": "Muehldorf A. Inn",
        "country_a": "DEU",
        "country": "Germany",
        "region": "Bayern",
        "county": "Muehldorf A. Inn",
        "confidence": 0.6729677786535914,
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
        "id": "11159:adm2:mx:mex:gustavo_a__madero",
        "layer": "county",
        "source": "qs",
        "name": "Gustavo A. Madero",
        "country_a": "MEX",
        "country": "Mexico",
        "region": "Distrito Federal",
        "county": "Gustavo A. Madero",
        "confidence": 0.6729677786535914,
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
        "id": "11173:adm2:mx:mex:general_canuto_a__neri",
        "layer": "county",
        "source": "qs",
        "name": "General Canuto A. Neri",
        "country_a": "MEX",
        "country": "Mexico",
        "region": "Guerrero",
        "county": "General Canuto A. Neri",
        "confidence": 0.6729677786535914,
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
        "confidence": 0.6729677786535914,
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
        "id": "6506:adm2:de:deu:altoetting",
        "layer": "county",
        "source": "qs",
        "name": "Altoetting",
        "country_a": "DEU",
        "country": "Germany",
        "region": "Bayern",
        "county": "Altoetting",
        "confidence": 0.6500151604412899,
        "label": "Altoetting, Bayern"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          12.7052878628714,
          48.2097847523116
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "6510:adm2:de:deu:augsburg",
        "layer": "county",
        "source": "qs",
        "name": "Augsburg",
        "country_a": "DEU",
        "country": "Germany",
        "region": "Bayern",
        "county": "Augsburg",
        "confidence": 0.6500151604412899,
        "label": "Augsburg, Bayern"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          10.8855198277615,
          48.3455674353699
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "6518:adm2:de:deu:aichach_friedberg",
        "layer": "county",
        "source": "qs",
        "name": "Aichach-Friedberg",
        "country_a": "DEU",
        "country": "Germany",
        "region": "Bayern",
        "county": "Aichach-Friedberg",
        "confidence": 0.6500151604412899,
        "label": "Aichach-Friedberg, Bayern"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          11.0527470230827,
          48.4275433889509
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "6521:adm2:de:deu:alb_donau_kreis",
        "layer": "county",
        "source": "qs",
        "name": "Alb-Donau-Kreis",
        "country_a": "DEU",
        "country": "Germany",
        "region": "Baden-Wã¼rttemberg",
        "county": "Alb-Donau-Kreis",
        "confidence": 0.6500151604412899,
        "label": "Alb-Donau-Kreis, Baden-Wã¼rttemberg"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          9.8274682228188,
          48.4016920001807
        ]
      }
    }
  ],
  "bbox": [
    -100.104177508501,
    15.2312424482025,
    12.7052878628714,
    48.4275433889509
  ]
}
```

## Tests

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
```

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
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

