# api root

*Generated: Fri Sep 18 2015 15:38:32 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/v1/"
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
  "content-type": "text/html; charset=utf-8",
  "content-length": "183",
  "etag": "W/\"b7-ndNiCU0qXcoWUhUOm1gWkw\"",
  "date": "Fri, 18 Sep 2015 13:38:32 GMT",
  "connection": "close"
}
```
```html
<style>html{font-family:monospace}</style><h1>Pelias API</h1>

<h3>Version: <a href="https://github.com/pelias/api/releases">1.0</a></h3>

<h2>DETAILED DOCUMENTATION COMING SOON!</h2>
```

## Tests

### ✓ content-type header correctly set
```javascript
response.should.have.header 'Content-Type','text/html; charset=utf-8'
```

### ✓ vanity header correctly set
```javascript
response.should.have.header 'X-Powered-By','mapzen'
```

### ✓ charset header correctly set
```javascript
response.should.have.header 'Charset','utf8'
```

### ✓ cache-control header correctly set
```javascript
response.should.have.header 'Cache-Control','public,max-age=60'
```

### ✓ server header correctly set
```javascript
response.should.have.header 'Server'
response.headers.server.should.match /Pelias\/\d{1,2}\.\d{1,2}\.\d{1,2}/
```

### ✓ endpoint available
```javascript
response.statusCode.should.be.equal 200
```

