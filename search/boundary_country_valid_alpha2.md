# bounding country

*Generated: Fri Sep 18 2015 15:38:36 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/search?text=a&boundary.country=US"
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
  "content-length": "3869",
  "etag": "W/\"f1d-fZU1Qdn62zsc987c426TMg\"",
  "date": "Fri, 18 Sep 2015 13:38:34 GMT",
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
      "boundary.country": "USA"
    },
    "engine": {
      "name": "Pelias",
      "author": "Mapzen",
      "version": "1.0"
    },
    "timestamp": 1442583514644
  },
  "type": "FeatureCollection",
  "features": [
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
        "confidence": 0.8803093108923947,
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
        "id": "4643:adm1:us:usa:alabama",
        "layer": "region",
        "source": "qs",
        "name": "Alabama",
        "country_a": "USA",
        "country": "United States",
        "region": "Alabama",
        "confidence": 0.8803093108923947,
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
        "id": "4621:adm1:us:usa:arkansas",
        "layer": "region",
        "source": "qs",
        "name": "Arkansas",
        "country_a": "USA",
        "country": "United States",
        "region": "Arkansas",
        "confidence": 0.8803093108923947,
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
        "id": "4625:adm1:us:usa:alaska",
        "layer": "region",
        "source": "qs",
        "name": "Alaska",
        "country_a": "USA",
        "country": "United States",
        "region": "Alaska",
        "confidence": 0.8803093108923947,
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
        "id": "16936:adm2:us:usa:alameda_county",
        "layer": "county",
        "source": "qs",
        "name": "Alameda County",
        "country_a": "USA",
        "country": "United States",
        "region": "California",
        "county": "Alameda County",
        "confidence": 0.6547937927384033,
        "label": "Alameda County, California"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -121.917890770705,
          37.6505455047888
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "14334:adm2:us:usa:allegheny_county",
        "layer": "county",
        "source": "qs",
        "name": "Allegheny County",
        "country_a": "USA",
        "country": "United States",
        "region": "Pennsylvania",
        "county": "Allegheny County",
        "confidence": 0.6547937927384033,
        "label": "Allegheny County, Pennsylvania"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -79.9811948694513,
          40.4688372501952
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "16489:adm2:us:usa:arlington_county",
        "layer": "county",
        "source": "qs",
        "name": "Arlington County",
        "country_a": "USA",
        "country": "United States",
        "region": "Virginia",
        "county": "Arlington County",
        "confidence": 0.6547937927384033,
        "label": "Arlington County, Virginia"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -77.1009376640765,
          38.8786140597829
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "15481:adm2:us:usa:anne_arundel_county",
        "layer": "county",
        "source": "qs",
        "name": "Anne Arundel County",
        "country_a": "USA",
        "country": "United States",
        "region": "Maryland",
        "county": "Anne Arundel County",
        "confidence": 0.6547937927384033,
        "label": "Anne Arundel County, Maryland"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -76.5676009657312,
          38.9941601044479
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "16457:adm2:us:usa:anchorage_municipality",
        "layer": "county",
        "source": "qs",
        "name": "Anchorage Municipality",
        "country_a": "USA",
        "country": "United States",
        "region": "Alaska",
        "county": "Anchorage Municipality",
        "confidence": 0.6547937927384033,
        "label": "Anchorage Municipality, Alaska"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -149.194731226161,
          61.1483408862527
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "id": "16434:adm2:us:usa:alachua_county",
        "layer": "county",
        "source": "qs",
        "name": "Alachua County",
        "country_a": "USA",
        "country": "United States",
        "region": "Florida",
        "county": "Alachua County",
        "confidence": 0.6547937927384033,
        "label": "Alachua County, Florida"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -82.3576997957445,
          29.6747567334525
        ]
      }
    }
  ],
  "bbox": [
    -151.593424452417,
    29.6747567334525,
    -76.5676009657312,
    63.7429911587519
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

### ✓ valid geojson
```javascript
json.type.should.be.equal 'FeatureCollection'
json.features.should.be.instanceof Array
```

### ✓ inputs
```javascript
json.geocoding.query['text'].should.eql 'a'
json.geocoding.query['size'].should.eql 10
json.geocoding.query['boundary.country'].should.eql 'USA'
```

### ✓ expected warnings
```javascript
should.not.exist json.geocoding.warnings
```

