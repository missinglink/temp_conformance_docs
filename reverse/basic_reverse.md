# basic reverse

*Generated: Fri Sep 18 2015 15:38:54 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=1&point.lon=2"
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
  "content-length": "3284",
  "etag": "W/\"cd4-Os1UVH/nKwmYOup4HBlMoQ\"",
  "date": "Fri, 18 Sep 2015 13:38:53 GMT",
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
      "point.lat": 1,
      "point.lon": 2,
      "boundary.circle.lat": 1,
      "boundary.circle.lon": 2
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583533932
  },
  "type": "FeatureCollection",
  "features": [
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
        "id": "2231:adm1:st:stp:s_o_tom_",
        "layer": "region",
        "source": "qs",
        "name": "São Tomé",
        "country_a": "STP",
        "country": "Sao Tome And Principe",
        "region": "São Tomé",
        "label": "São Tomé"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          6.60763536221871,
          0.235564719013799
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "269:adm0:st:stp:_",
        "layer": "country",
        "source": "qs",
        "name": "Sao Tome And Principe",
        "country_a": "STP",
        "country": "Sao Tome And Principe",
        "label": "Sao Tome And Principe"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          6.70056983012515,
          0.411288773978794
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
        "id": "263:adm1:bj:ben:littoral",
        "layer": "region",
        "source": "qs",
        "name": "Littoral",
        "country_a": "BEN",
        "country": "Benin",
        "region": "Littoral",
        "label": "Littoral"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          2.42406359110576,
          6.36361810688231
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "2232:adm1:st:stp:pr_ncipe",
        "layer": "region",
        "source": "qs",
        "name": "Príncipe",
        "country_a": "STP",
        "country": "Sao Tome And Principe",
        "region": "Príncipe",
        "label": "Príncipe"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          7.39591632558385,
          1.62024607562631
        ]
      }
    }
  ],
  "bbox": [
    -0.216653655604662,
    -1.44642237936086,
    7.39591632558385,
    6.36361810688231
  ]
}
```

## Tests

### ✓ inputs
```javascript
json.geocoding.query['point.lat'].should.eql 1
json.geocoding.query['point.lon'].should.eql 2
json.geocoding.query['size'].should.eql 10
```

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

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

