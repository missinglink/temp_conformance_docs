# layer alias

*Generated: Fri Sep 18 2015 15:38:39 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&layers=coarse"
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
  "content-length": "3927",
  "etag": "W/\"f57-CtDvhZ/wTrIa8YTSXoJAUA\"",
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
      "types": {
        "from_address_parsing": [
          "admin0",
          "admin1",
          "admin2",
          "neighborhood",
          "locality",
          "local_admin"
        ],
        "from_layers": [
          "admin0",
          "admin1",
          "admin2",
          "neighborhood",
          "locality",
          "local_admin"
        ]
      },
      "size": 10,
      "private": false,
      "type": [
        "admin0",
        "admin1",
        "admin2",
        "neighborhood",
        "locality",
        "local_admin"
      ]
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583516675
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
        "id": "275:adm0:au:aus:_",
        "layer": "country",
        "source": "qs",
        "name": "Australia",
        "country_a": "AUS",
        "country": "Australia",
        "confidence": 0.6500151604412899,
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
        "id": "154:adm0:ar:arg:_",
        "layer": "country",
        "source": "qs",
        "name": "Argentina",
        "country_a": "ARG",
        "country": "Argentina",
        "confidence": 0.6500151604412899,
        "label": "Argentina"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -65.1673660041751,
          -35.3864080843045
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "271:adm0:am:arm:_",
        "layer": "country",
        "source": "qs",
        "name": "Armenia",
        "country_a": "ARM",
        "country": "Armenia",
        "confidence": 0.6500151604412899,
        "label": "Armenia"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          44.9389534911001,
          40.2946817758956
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "233:adm0:az:aze:_",
        "layer": "country",
        "source": "qs",
        "name": "Azerbaijan",
        "country_a": "AZE",
        "country": "Azerbaijan",
        "confidence": 0.6500151604412899,
        "label": "Azerbaijan"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          47.6640940329042,
          40.3738398799229
        ]
      }
    }
  ],
  "bbox": [
    -100.104177508501,
    -35.3864080843045,
    134.490286361248,
    48.2393018867677
  ]
}
```

## Tests

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

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
json.geocoding.query.types['from_layers'].should.eql ["admin0","admin1","admin2","neighborhood","locality","local_admin"]
json.geocoding.query['type'].should.eql ["admin0","admin1","admin2","neighborhood","locality","local_admin"]
```

