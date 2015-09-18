# cross-origin resource sharing

*Generated: Fri Sep 18 2015 15:39:10 GMT+0200 (CEST)*
## Request
```javascript
{
  "protocol": "http:",
  "host": "localhost",
  "method": "GET",
  "port": 3100,
  "path": "/"
}
```

## Response
```javascript
Status: 500
{
  "x-powered-by": "mapzen",
  "charset": "utf8",
  "cache-control": "no-cache",
  "server": "Pelias/2.2.0",
  "access-control-allow-origin": "*",
  "access-control-allow-methods": "GET, OPTIONS",
  "access-control-allow-headers": "X-Requested-With,content-type",
  "access-control-allow-credentials": "true",
  "content-type": "application/json; charset=utf-8",
  "content-length": "51",
  "etag": "W/\"33-6HINdxxv5uP56TatT8vZWQ\"",
  "date": "Fri, 18 Sep 2015 13:39:09 GMT",
  "connection": "close"
}
```
```javascript
{
  "error": "Invalid path, no legacy proxy specified"
}
```

## Tests

### ✓ access control headers correctly set
```javascript
response.should.have.header 'Access-Control-Allow-Origin','*'
response.should.have.header 'Access-Control-Allow-Methods','GET, OPTIONS'
response.should.have.header 'Access-Control-Allow-Headers','X-Requested-With,content-type'
response.should.have.header 'Access-Control-Allow-Credentials','true'
```

