# set size

*Generated: Fri Sep 18 2015 15:39:13 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=1&point.lon=1&size=999"
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
  "content-length": "11238",
  "etag": "W/\"2be6-G+yQSpGhCOGKyYpTKOFZvQ\"",
  "date": "Fri, 18 Sep 2015 13:39:06 GMT",
  "connection": "close"
}
```
```javascript
{
  "geocoding": {
    "version": "0.1",
    "attribution": "http://pelias.mapzen.com/v1/attribution",
    "query": {
      "size": 40,
      "private": false,
      "point.lat": 1,
      "point.lon": 1,
      "boundary.circle.lat": 1,
      "boundary.circle.lon": 1
    },
    "warnings": [
      "out-of-range integer 'size', using MAX_SIZE"
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583546838
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
        "id": "2510:adm1:tg:tgo:maritime",
        "layer": "region",
        "source": "qs",
        "name": "Maritime",
        "country_a": "TGO",
        "country": "Togo",
        "region": "Maritime",
        "label": "Maritime"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          1.26773307874029,
          6.48753343990315
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
        "id": "268:adm1:bj:ben:mono",
        "layer": "region",
        "source": "qs",
        "name": "Mono",
        "country_a": "BEN",
        "country": "Benin",
        "region": "Mono",
        "label": "Mono"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          1.82758541507066,
          6.52291741385979
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
        "id": "262:adm1:bj:ben:atlantique",
        "layer": "region",
        "source": "qs",
        "name": "Atlantique",
        "country_a": "BEN",
        "country": "Benin",
        "region": "Atlantique",
        "label": "Atlantique"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          2.22015514398014,
          6.59812615878897
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
        "id": "265:adm1:bj:ben:ou_m_",
        "layer": "region",
        "source": "qs",
        "name": "Ouémé",
        "country_a": "BEN",
        "country": "Benin",
        "region": "Ouémé",
        "label": "Ouémé"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          2.53930161172855,
          6.62927469806837
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
        "id": "381:_:_:nga:ikoyi",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Ikoyi",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Lagos",
        "county": "Eti-Osa",
        "label": "Ikoyi, Eti-Osa, Lagos"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          3.43251548461127,
          6.44665705541562
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "264:adm1:bj:ben:kouffo",
        "layer": "region",
        "source": "qs",
        "name": "Kouffo",
        "country_a": "BEN",
        "country": "Benin",
        "region": "Kouffo",
        "label": "Kouffo"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          1.77388079399811,
          6.9981896030985
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1784:adm1:ng:nga:lagos",
        "layer": "region",
        "source": "qs",
        "name": "Lagos",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Lagos",
        "label": "Lagos"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          3.55237364181542,
          6.52254803414954
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
        "id": "865:adm1:gh:gha:volta",
        "layer": "region",
        "source": "qs",
        "name": "Volta",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Volta",
        "label": "Volta"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          0.400262152815621,
          7.23525500910746
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "859:adm1:gh:gha:ashanti",
        "layer": "region",
        "source": "qs",
        "name": "Ashanti",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Ashanti",
        "label": "Ashanti"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -1.44617264152778,
          6.80808280609781
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1779:adm1:ng:nga:bayelsa",
        "layer": "region",
        "source": "qs",
        "name": "Bayelsa",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Bayelsa",
        "label": "Bayelsa"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          6.10422656993389,
          4.77452890539033
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "266:adm1:bj:ben:zou",
        "layer": "region",
        "source": "qs",
        "name": "Zou",
        "country_a": "BEN",
        "country": "Benin",
        "region": "Zou",
        "label": "Zou"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          2.1101912733229,
          7.265426638824
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "267:adm1:bj:ben:plateau",
        "layer": "region",
        "source": "qs",
        "name": "Plateau",
        "country_a": "BEN",
        "country": "Benin",
        "region": "Plateau",
        "label": "Plateau"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          2.62520202469022,
          7.18670937411393
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
    },
    {
      "type": "Feature",
      "properties": {
        "id": "2509:adm1:tg:tgo:plateaux",
        "layer": "region",
        "source": "qs",
        "name": "Plateaux",
        "country_a": "TGO",
        "country": "Togo",
        "region": "Plateaux",
        "label": "Plateaux"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          1.11576497291894,
          7.43692358110169
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1786:adm1:ng:nga:ogun",
        "layer": "region",
        "source": "qs",
        "name": "Ogun",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Ogun",
        "label": "Ogun"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          3.46214013517358,
          7.00080366509584
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1794:adm1:ng:nga:delta",
        "layer": "region",
        "source": "qs",
        "name": "Delta",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Delta",
        "label": "Delta"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          5.95873054894032,
          5.71649964289834
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1778:adm1:ng:nga:rivers",
        "layer": "region",
        "source": "qs",
        "name": "Rivers",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Rivers",
        "label": "Rivers"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          6.90854572083605,
          4.88002828125345
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "524:adm1:ci:civ:lagunes",
        "layer": "region",
        "source": "qs",
        "name": "Lagunes",
        "country_a": "CIV",
        "country": "Ivory Coast",
        "region": "Lagunes",
        "label": "Lagunes"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -4.37097911868115,
          5.60144503466922
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "522:adm1:ci:civ:agn_by",
        "layer": "region",
        "source": "qs",
        "name": "Agnéby",
        "country_a": "CIV",
        "country": "Ivory Coast",
        "region": "Agnéby",
        "label": "Agnéby"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -3.9967579600367,
          6.06758626519747
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "526:adm1:ci:civ:moyen_comoe",
        "layer": "region",
        "source": "qs",
        "name": "Moyen-Comoe",
        "country_a": "CIV",
        "country": "Ivory Coast",
        "region": "Moyen-Comoe",
        "label": "Moyen-Comoe"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -3.4305546510337,
          6.69609505821048
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "860:adm1:gh:gha:brong_ahafo",
        "layer": "region",
        "source": "qs",
        "name": "Brong Ahafo",
        "country_a": "GHA",
        "country": "Ghana",
        "region": "Brong Ahafo",
        "label": "Brong Ahafo"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -1.65996436776451,
          7.7097446583085
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "261:adm1:bj:ben:collines",
        "layer": "region",
        "source": "qs",
        "name": "Collines",
        "country_a": "BEN",
        "country": "Benin",
        "region": "Collines",
        "label": "Collines"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          2.19428934974021,
          8.12276260841707
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1787:adm1:ng:nga:ondo",
        "layer": "region",
        "source": "qs",
        "name": "Ondo",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Ondo",
        "label": "Ondo"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          5.15951711512651,
          6.91114318058506
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "13:adm0:gh:gha:_",
        "layer": "country",
        "source": "qs",
        "name": "Ghana",
        "country_a": "GHA",
        "country": "Ghana",
        "label": "Ghana"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -1.20593880288775,
          7.96521879390477
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1789:adm1:ng:nga:osun",
        "layer": "region",
        "source": "qs",
        "name": "Osun",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Osun",
        "label": "Osun"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          4.5357864338936,
          7.53444002534425
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1795:adm1:ng:nga:edo",
        "layer": "region",
        "source": "qs",
        "name": "Edo",
        "country_a": "NGA",
        "country": "Nigeria",
        "region": "Edo",
        "label": "Edo"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          5.91164531247706,
          6.62608682330295
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "217:adm0:tg:tgo:_",
        "layer": "country",
        "source": "qs",
        "name": "Togo",
        "country_a": "TGO",
        "country": "Togo",
        "label": "Togo"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          0.97878892306899,
          8.53180705576601
        ]
      }
    }
  ],
  "bbox": [
    -4.37097911868115,
    -1.44642237936086,
    7.39591632558385,
    8.53180705576601
  ]
}
```

## Tests

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
json.geocoding.query['size'].should.eql 40
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

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
```

### ✓ expected warnings
```javascript
should.exist json.geocoding.warnings
json.geocoding.warnings.should.eql [ 'out-of-range integer \'size\', using MAX_SIZE' ]
```

