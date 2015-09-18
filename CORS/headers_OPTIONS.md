# cross-origin resource sharing

*Generated: Fri Sep 18 2015 15:39:14 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "OPTIONS",
  "port": 3100,
  "path": "/"
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
  "content-type": "text/plain; charset=utf-8",
  "content-length": "2",
  "etag": "W/\"2-4KoCHiHd29bYzs7HHpz1ZA\"",
  "date": "Fri, 18 Sep 2015 13:39:13 GMT",
  "connection": "close"
}
```
```html
OK
```

## Tests

### ✓ access control headers correctly set
```javascript
response.should.have.header 'Access-Control-Allow-Origin','*'
response.should.have.header 'Access-Control-Allow-Methods','GET, OPTIONS'
response.should.have.header 'Access-Control-Allow-Headers','X-Requested-With,content-type'
response.should.have.header 'Access-Control-Allow-Credentials','true'
```

