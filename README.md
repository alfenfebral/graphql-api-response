# rest-api-response
Rest API Response

## Rest API Popular Endpoint Formats

> https://example.com/graphql

## Rest API Success Responses

1- GET - Get single item - HTTP Response Code: **200**
```javascript
    HTTP/1.1 200
    Content-Type: application/json

    {
        "status": "success",
        "code": 200,
        "data": {
            "name": "Item 1"
        }
    }
```
