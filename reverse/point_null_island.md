# point null island

*Generated: Fri Sep 18 2015 15:39:10 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=0&point.lon=0"
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
  "content-length": "3228",
  "etag": "W/\"c9c-AcQeq8EJeTr/VIOmsZiXhQ\"",
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
      "size": 10,
      "private": false,
      "point.lat": 0,
      "point.lon": 0,
      "boundary.circle.lat": 0,
      "boundary.circle.lon": 0
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583549135
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
        "id": "374:_:_:gha:nima",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Nima",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Greater Accra",
        "label": "Nima, Greater Accra"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -0.206193414239056,
          5.58690323422261
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
    },
    {
      "type": "Feature",
      "properties": {
        "id": "861:adm1:gh:gha:central",
        "layer": "region",
        "source": "qs",
        "name": "Central",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Central",
        "label": "Central"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -1.19397495727289,
          5.56005344014801
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "864:adm1:gh:gha:greater_accra",
        "layer": "region",
        "source": "qs",
        "name": "Greater Accra",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Greater Accra",
        "label": "Greater Accra"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          0.0638774738231792,
          5.77659538324999
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "915:adm1:gq:gnq:annob_n",
        "layer": "region",
        "source": "qs",
        "name": "Annobón",
        "country_a": "GNQ",
        "country": "Equatorial Guinea",
        "region": "Annobón",
        "label": "Annobón"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          5.63132684908647,
          -1.44642237936086
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "863:adm1:gh:gha:western",
        "layer": "region",
        "source": "qs",
        "name": "Western",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Western",
        "label": "Western"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -2.42471082784995,
          5.75017601370009
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "528:adm1:ci:civ:sud_como_",
        "layer": "region",
        "source": "qs",
        "name": "Sud-Comoé",
        "country_a": "CIV",
        "country": "Ivory Coast",
        "region": "Sud-Comoé",
        "label": "Sud-Comoé"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -3.13338103502947,
          5.54215913774781
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "862:adm1:gh:gha:eastern",
        "layer": "region",
        "source": "qs",
        "name": "Eastern",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Eastern",
        "label": "Eastern"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -0.425572467695167,
          6.40272395694289
        ]
      }
    }
  ],
  "bbox": [
    -3.13338103502947,
    -1.44642237936086,
    5.63132684908647,
    6.40272395694289
  ]
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
json.geocoding.query['size'].should.eql 10
json.geocoding.query['point.lat'].should.eql 0
json.geocoding.query['point.lon'].should.eql 0
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

