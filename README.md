# rest-api-response
Rest API Response

## Rest API Popular Endpoint Formats

> https://example.com/graphql

## Converter For Remove Newline and Indent
http://removelinebreaks.net/

## How to convert from graphql playground
1. Copy text from graphql playground tab


## Rest API Success Responses

1- POST - Get All Item - HTTP Response Code: **200**
```javascript
    HTTP/1.1 200
    Content-Type: application/json
 
    ---Request Body--
    {
    	"query": "query { books { id name genre imageUrl author { id name age } } }"
    }
    ---End Request Body---
    
    ---Response---
    {
        "status": "success",
        "code": 200,
        "data": {
            "name": "Item 1"
        }
    }
    ---End Response---
```
