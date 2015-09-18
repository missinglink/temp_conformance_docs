# bounding country

*Generated: Fri Sep 18 2015 15:39:03 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=1&point.lon=1&boundary.country=US"
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
  "content-length": "3629",
  "etag": "W/\"e2d-r65TX2EOMOJkCqq/lLA3Ew\"",
  "date": "Fri, 18 Sep 2015 13:39:00 GMT",
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
      "point.lon": 1,
      "boundary.circle.lat": 1,
      "boundary.circle.lon": 1,
      "boundary.country": "USA"
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583540121
  },
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "id": "29392:locality:us:usa:frederiksted",
        "layer": "locality",
        "source": "qs",
        "name": "Frederiksted",
        "country_a": "USA",
        "country": "United States",
        "label": "Frederiksted, United States"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -64.8818572774714,
          17.7123305658789
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "29398:locality:us:usa:charlotte_amalie_west",
        "layer": "locality",
        "source": "qs",
        "name": "Charlotte Amalie West",
        "country_a": "USA",
        "country": "United States",
        "label": "Charlotte Amalie West, United States"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -64.9627234212986,
          18.3384696327538
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "19650:_:_:usa:south_lubec",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "South Lubec",
        "country_a": "USA",
        "country": "United States",
        "region": "Maine",
        "county": "Washington",
        "label": "South Lubec, Washington, Maine"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -66.9894430519835,
          44.8436116533116
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "10805:locality:us:usa:lubec",
        "layer": "locality",
        "source": "qs",
        "name": "Lubec",
        "country_a": "USA",
        "country": "United States",
        "region": "Maine",
        "label": "Lubec, Maine"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -66.9898191976483,
          44.8550833382414
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "87104:localadmin:us:usa:lubec",
        "layer": "localadmin",
        "source": "qs",
        "name": "Lubec",
        "country_a": "USA",
        "country": "United States",
        "region": "Maine",
        "county": "Washington",
        "label": "Lubec, Washington, Maine"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -67.0448781105103,
          44.841640902561
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "10776:locality:us:usa:eastport",
        "layer": "locality",
        "source": "qs",
        "name": "Eastport",
        "country_a": "USA",
        "country": "United States",
        "region": "Maine",
        "label": "Eastport, Maine"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -67.0112034988563,
          44.9146458009121
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "87100:localadmin:us:usa:eastport",
        "layer": "localadmin",
        "source": "qs",
        "name": "Eastport",
        "country_a": "USA",
        "country": "United States",
        "region": "Maine",
        "county": "Washington",
        "label": "Eastport, Washington, Maine"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -67.0181597330886,
          44.9123183119129
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "15274:_:_:usa:little_machias",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Little Machias",
        "country_a": "USA",
        "country": "United States",
        "region": "Maine",
        "county": "Washington",
        "label": "Little Machias, Washington, Maine"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -67.2198720530783,
          44.6585054816168
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "86899:localadmin:us:usa:cutler",
        "layer": "localadmin",
        "source": "qs",
        "name": "Cutler",
        "country_a": "USA",
        "country": "United States",
        "region": "Maine",
        "county": "Washington",
        "label": "Cutler, Washington, Maine"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -67.2248333477353,
          44.6828959725841
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "87134:localadmin:us:usa:passamaquoddy_pleasant_point",
        "layer": "localadmin",
        "source": "qs",
        "name": "Passamaquoddy Pleasant Point",
        "country_a": "USA",
        "country": "United States",
        "region": "Maine",
        "county": "Washington",
        "label": "Passamaquoddy Pleasant Point, Washington, Maine"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -67.0567262818866,
          44.9623808999288
        ]
      }
    }
  ],
  "bbox": [
    -67.2248333477353,
    17.7123305658789,
    -64.8818572774714,
    44.9623808999288
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

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
```

### ✓ inputs
```javascript
json.geocoding.query['size'].should.eql 10
json.geocoding.query['boundary.country'].should.eql 'USA'
```

