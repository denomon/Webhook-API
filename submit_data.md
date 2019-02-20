# Webhook Submission

Once registered and activated and have retrieved your access token. You can now submit data to the webhook url


### JSON representation

 `POST /api/statements`.

<!-- { "blockType": "resource",
"@type": "author",
"optionalProperties": [] } -->
```json
{
	"payload": {
          "key1":"value1",
          "key2":"value2",
          "key3":"value3"
        }
}
```

200 Created  - indicates that the request has succeeded.


```json
{
    "message": "Successfully received data"
}
```


401 Unauthorized - indicates the user making the request has not been activated.


```json
{
      "error": "account not activated, contact admin"
}
```
### Properties

| Property | Type | Description |
|:---------|:-----|:------------|
| **payload**   | Json | json key value pair. |


<!-- {
"type": "#page.annotation",
"description": "",
"keywords": "",
"section": "",
"tocPath": "",
"tocBookmarks": {}
} -->
