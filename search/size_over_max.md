# set size

*Generated: Fri Sep 18 2015 15:38:43 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&size=999"
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
  "content-length": "12843",
  "etag": "W/\"322b-PVpt1Pz08Up7TmNbE+pl/w\"",
  "date": "Fri, 18 Sep 2015 13:38:39 GMT",
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
      "size": 40,
      "private": false
    },
    "warnings": [
      "out-of-range integer 'size', using MAX_SIZE"
    ],
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583519924
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
        "confidence": 0.9040461792436302,
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
        "confidence": 0.8960846163885059,
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
        "confidence": 0.8916484774719946,
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
        "confidence": 0.8916484774719946,
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
        "confidence": 0.8916484774719946,
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
        "confidence": 0.8916484774719946,
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
        "confidence": 0.6598022145435259,
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
        "confidence": 0.6598022145435259,
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
        "confidence": 0.6598022145435259,
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
        "confidence": 0.6598022145435259,
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
        "confidence": 0.6598022145435259,
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
        "confidence": 0.6598022145435259,
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
        "confidence": 0.6598022145435259,
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
        "confidence": 0.6598022145435259,
        "label": "Albania"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          20.0664303302927,
          41.1391311962901
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "54:adm0:ao:ago:_",
        "layer": "country",
        "source": "qs",
        "name": "Angola",
        "country_a": "AGO",
        "country": "Angola",
        "confidence": 0.6598022145435259,
        "label": "Angola"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          17.5478886905547,
          -12.2989942123002
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "55:adm0:ai:aia:_",
        "layer": "country",
        "source": "qs",
        "name": "Anguilla",
        "country_a": "AIA",
        "country": "Anguilla",
        "confidence": 0.6598022145435259,
        "label": "Anguilla"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -63.0639045946057,
          18.2312161906986
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "247:adm0:aq:ata:_",
        "layer": "country",
        "source": "qs",
        "name": "Antarctica",
        "country_a": "ATA",
        "country": "Antarctica",
        "confidence": 0.6598022145435259,
        "label": "Antarctica"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          14.8213328979243,
          -80.2341515108868
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "248:adm0:az:aze:_",
        "layer": "country",
        "source": "qs",
        "name": "Azerbaijan",
        "country_a": "AZE",
        "country": "Azerbaijan",
        "confidence": 0.6598022145435259,
        "label": "Azerbaijan"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          46.6328475612312,
          39.765319861458
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "274:adm0:fi:ald:_",
        "layer": "country",
        "source": "qs",
        "name": "Aland",
        "country_a": "ALD",
        "country": "Aland",
        "confidence": 0.6598022145435259,
        "label": "Aland"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          20.2701396793432,
          60.1604264731896
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
        "confidence": 0.6598022145435259,
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
        "confidence": 0.6598022145435259,
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
        "id": "4643:adm1:us:usa:alabama",
        "layer": "region",
        "source": "qs",
        "name": "Alabama",
        "country_a": "USA",
        "country": "United States",
        "region": "Alabama",
        "confidence": 0.6598022145435259,
        "label": "Alabama"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -86.8445207407337,
          32.7568836722904
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "13674:adm2:nz:nzl:auckland",
        "layer": "county",
        "source": "qs",
        "name": "Auckland",
        "country_a": "NZL",
        "country": "New Zealand",
        "county": "Auckland",
        "confidence": 0.6598022145435259,
        "label": "Auckland, New Zealand"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          174.730898002879,
          -36.7076639975346
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "4621:adm1:us:usa:arkansas",
        "layer": "region",
        "source": "qs",
        "name": "Arkansas",
        "country_a": "USA",
        "country": "United States",
        "region": "Arkansas",
        "confidence": 0.6598022145435259,
        "label": "Arkansas"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -92.4392389083154,
          34.8997723376764
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "706:adm2:be:bel:antwerpen",
        "layer": "county",
        "source": "qs",
        "name": "Antwerpen",
        "country_a": "BEL",
        "country": "Belgium",
        "region": "Antwerpen",
        "county": "Antwerpen",
        "confidence": 0.6598022145435259,
        "label": "Antwerpen"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          4.50591510815915,
          51.2806525350398
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "3196:adm1:be:bel:antwerpen",
        "layer": "region",
        "source": "qs",
        "name": "Antwerpen",
        "country_a": "BEL",
        "country": "Belgium",
        "region": "Antwerpen",
        "confidence": 0.6598022145435259,
        "label": "Antwerpen"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          4.7196553225824,
          51.2295217247864
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "4625:adm1:us:usa:alaska",
        "layer": "region",
        "source": "qs",
        "name": "Alaska",
        "country_a": "USA",
        "country": "United States",
        "region": "Alaska",
        "confidence": 0.6598022145435259,
        "label": "Alaska"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -151.593424452417,
          63.7429911587519
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "131:adm2:au:aus:adelaide",
        "layer": "county",
        "source": "qs",
        "name": "Adelaide",
        "country_a": "AUS",
        "country": "Australia",
        "region": "South Australia",
        "county": "Adelaide",
        "confidence": 0.6598022145435259,
        "label": "Adelaide, South Australia"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          138.598934905756,
          -34.922002203103
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1181:adm1:jp:jpn:aichi",
        "layer": "region",
        "source": "qs",
        "name": "Aichi",
        "country_a": "JPN",
        "country": "Japan",
        "region": "Aichi",
        "confidence": 0.6598022145435259,
        "label": "Aichi"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          137.201263762546,
          35.0266748507897
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "574:adm1:co:col:antioquia",
        "layer": "region",
        "source": "qs",
        "name": "Antioquia",
        "country_a": "COL",
        "country": "Colombia",
        "region": "Antioquia",
        "confidence": 0.6598022145435259,
        "label": "Antioquia"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -75.5810754144621,
          6.9225943875745
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "3505:adm1:fr:fra:alpes_maritimes",
        "layer": "region",
        "source": "qs",
        "name": "Alpes-Maritimes",
        "country_a": "FRA",
        "country": "France",
        "region": "Alpes-Maritimes",
        "confidence": 0.6598022145435259,
        "label": "Alpes-Maritimes"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          7.11635512560706,
          43.938032655233
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "6692:adm2:de:deu:aachen",
        "layer": "county",
        "source": "qs",
        "name": "Aachen",
        "country_a": "DEU",
        "country": "Germany",
        "region": "Nordrhein-Westfalen",
        "county": "Aachen",
        "confidence": 0.6598022145435259,
        "label": "Aachen, Nordrhein-Westfalen"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          6.21691006611092,
          50.7275832903832
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "10361:adm2:fr:fra:aubervilliers",
        "layer": "county",
        "source": "qs",
        "name": "Aubervilliers",
        "country_a": "FRA",
        "country": "France",
        "region": "Seine-Saint-Denis",
        "county": "Aubervilliers",
        "confidence": 0.6598022145435259,
        "label": "Aubervilliers, Seine-Saint-Denis"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          2.38446056728088,
          48.9121730139084
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "3392:adm1:es:esp:asturias",
        "layer": "region",
        "source": "qs",
        "name": "Asturias",
        "country_a": "ESP",
        "country": "Spain",
        "region": "Asturias",
        "confidence": 0.6598022145435259,
        "label": "Asturias"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -5.99363313799892,
          43.2924007242994
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "3362:adm1:es:esp:alicante_alacant",
        "layer": "region",
        "source": "qs",
        "name": "Alicante/alacant",
        "country_a": "ESP",
        "country": "Spain",
        "region": "Alicante/alacant",
        "confidence": 0.6598022145435259,
        "label": "Alicante/alacant"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -0.568599919645069,
          38.4785920946062
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "27:adm2:au:aus:auburn",
        "layer": "county",
        "source": "qs",
        "name": "Auburn",
        "country_a": "AUS",
        "country": "Australia",
        "region": "New South Wales",
        "county": "Auburn",
        "confidence": 0.6598022145435259,
        "label": "Auburn, New South Wales"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          151.045761213533,
          -33.8549451862562
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1157:adm1:jo:jor:amman",
        "layer": "region",
        "source": "qs",
        "name": "Amman",
        "country_a": "JOR",
        "country": "Jordan",
        "region": "Amman",
        "confidence": 0.6598022145435259,
        "label": "Amman"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          36.3428120997147,
          31.5782837314241
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "2708:adm1:tr:tur:ankara",
        "layer": "region",
        "source": "qs",
        "name": "Ankara",
        "country_a": "TUR",
        "country": "Turkey",
        "region": "Ankara",
        "confidence": 0.6598022145435259,
        "label": "Ankara"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          32.6097704567825,
          39.7807852014427
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "1895:adm1:pe:per:arequipa",
        "layer": "region",
        "source": "qs",
        "name": "Arequipa",
        "country_a": "PER",
        "country": "Peru",
        "region": "Arequipa",
        "confidence": 0.6598022145435259,
        "label": "Arequipa"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -72.4591469284381,
          -15.8532674963226
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "3232:adm1:br:bra:amazonas",
        "layer": "region",
        "source": "qs",
        "name": "Amazonas",
        "country_a": "BRA",
        "country": "Brazil",
        "region": "Amazonas",
        "confidence": 0.6598022145435259,
        "label": "Amazonas"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -64.6530916295316,
          -4.15418523702874
        ]
      }
    }
  ],
  "bbox": [
    -151.593424452417,
    -80.2341515108868,
    174.730898002879,
    63.7429911587519
  ]
}
```

## Tests

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 40
```

### ✓ 200 ok
```javascript
response.statusCode.should.be.equal 200
response.should.have.header 'charset', 'utf8'
response.should.have.header 'content-type', 'application/json; charset=utf-8'
```

### ✓ expected warnings
```javascript
should.exist json.geocoding.warnings
json.geocoding.warnings.should.eql [ 'out-of-range integer \'size\', using MAX_SIZE' ]
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

