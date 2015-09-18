# point

*Generated: Fri Sep 18 2015 15:39:00 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/reverse?point.lat=40.744243&point.lon=-73.990342"
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
  "content-length": "3735",
  "etag": "W/\"e97-7NK/XS+zJbhS6bGDuDXBfQ\"",
  "date": "Fri, 18 Sep 2015 13:38:59 GMT",
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
      "point.lat": 40.744243,
      "point.lon": -73.990342,
      "boundary.circle.lat": 40.744243,
      "boundary.circle.lon": -73.990342
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583539713
  },
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "id": "25649:_:_:usa:flatiron_district",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Flatiron District",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Flatiron District, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9908583016,
          40.7432770374939
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "24074:_:_:usa:midtown_south",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Midtown South",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Midtown South, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9884788947629,
          40.741516995007
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "25714:_:_:usa:koreatown",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Koreatown",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Koreatown, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9865076596737,
          40.7487642932539
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "24078:_:_:usa:flatiron",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Flatiron",
        "country_a": "USA",
        "county": "Manhattan",
        "label": "Flatiron, Manhattan"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9840185081839,
          40.7463018523915
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "25116:_:_:usa:rose_hill",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Rose Hill",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Rose Hill, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9838277402303,
          40.742243674925
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "35925:_:_:usa:union_square",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Union Square",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Union Square, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9932343027843,
          40.7376776062632
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "24684:_:_:usa:garment_district",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Garment District",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Garment District, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9929959420188,
          40.7511683701002
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "35912:_:_:usa:gramercy_flatiron",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Gramercy-Flatiron",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Gramercy-Flatiron, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9862054707495,
          40.7368505544462
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "25863:_:_:usa:tenderloin",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Tenderloin",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Tenderloin, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9831781301724,
          40.7522668709346
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "24076:_:_:usa:gramercy",
        "layer": "neighbourhood",
        "source": "qs",
        "name": "Gramercy",
        "country_a": "USA",
        "country": "United States",
        "region": "New York",
        "county": "Manhattan",
        "label": "Gramercy, Manhattan, New York"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -73.9846609093552,
          40.7338898471015
        ]
      }
    }
  ],
  "bbox": [
    -73.9932343027843,
    40.7338898471015,
    -73.9831781301724,
    40.7522668709346
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

### ✓ expected errors
```javascript
should.not.exist json.geocoding.errors
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

### ✓ 200 ok
```javascript
response.statusCode.should.be.equal 200
response.should.have.header 'charset', 'utf8'
response.should.have.header 'content-type', 'application/json; charset=utf-8'
```

### ✓ inputs
```javascript
json.geocoding.query['size'].should.eql 10
json.geocoding.query['point.lat'].should.eql 40.744243
json.geocoding.query['point.lon'].should.eql -73.990342
```

