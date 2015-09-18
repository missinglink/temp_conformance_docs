# layer alias

*Generated: Fri Sep 18 2015 15:38:41 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&layers=country,region"
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
  "content-length": "3374",
  "etag": "W/\"d2e-7vtbzbUsWCVmi0W9JYfJGw\"",
  "date": "Fri, 18 Sep 2015 13:38:38 GMT",
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
          "admin1"
        ]
      },
      "size": 10,
      "private": false,
      "type": [
        "admin0",
        "admin1"
      ]
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583518551
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
        "confidence": 0.8946044986758963,
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
        "id": "982:adm1:hn:hnd:gracias_a_dios",
        "layer": "region",
        "source": "qs",
        "name": "Gracias A Dios",
        "country_a": "HND",
        "country": "Honduras",
        "region": "Gracias A Dios",
        "confidence": 0.8845859828471763,
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
        "confidence": 0.6588511898096159,
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
        "confidence": 0.6588511898096159,
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
        "confidence": 0.6588511898096159,
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
        "confidence": 0.6588511898096159,
        "label": "Azerbaijan"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          47.6640940329042,
          40.3738398799229
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "60:adm0:aw:abw:_",
        "layer": "country",
        "source": "qs",
        "name": "Aruba",
        "country_a": "ABW",
        "country": "Aruba",
        "confidence": 0.6588511898096159,
        "label": "Aruba"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -69.9705088304121,
          12.5134897244105
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "130:adm0:dz:dza:_",
        "layer": "country",
        "source": "qs",
        "name": "Algeria",
        "country_a": "DZA",
        "country": "Algeria",
        "confidence": 0.6588511898096159,
        "label": "Algeria"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          2.67569737486907,
          28.1503430963921
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "31:adm0:af:afg:_",
        "layer": "country",
        "source": "qs",
        "name": "Afghanistan",
        "country_a": "AFG",
        "country": "Afghanistan",
        "confidence": 0.6588511898096159,
        "label": "Afghanistan"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          66.0265208314839,
          33.8315944393331
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "109:adm0:al:alb:_",
        "layer": "country",
        "source": "qs",
        "name": "Albania",
        "country_a": "ALB",
        "country": "Albania",
        "confidence": 0.6588511898096159,
        "label": "Albania"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          20.0664303302927,
          41.1391311962901
        ]
      }
    }
  ],
  "bbox": [
    -84.3596374442632,
    -35.3864080843045,
    134.490286361248,
    43.1260515324895
  ]
}
```

## Tests

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
json.geocoding.query.types['from_layers'].should.eql ["admin0","admin1"]
json.geocoding.query['type'].should.eql ["admin0","admin1"]
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

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
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

