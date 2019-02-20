# Login

Once registered and activated, Log in to get your  access token. 


### JSON representation

 `POST /api/auth/login`.
 
  `Content-Type:application/json`


<!-- { "blockType": "resource",
"@type": "author",
"optionalProperties": [] } -->
```json
{
	"email":"test@test.com",
	"password":"password"
}
```

200 indicates that the request has succeeded.


```json
{
    "access_token": "your_access_token",
    "token_type": "Bearer",
    "expires_at": "2020-02-19 22:37:50"
}
```
### Properties

| Property | Type | Description |
|:---------|:-----|:------------|
| **email** | email | The email address. |
| **password** | String | the password. |


<!-- {
"type": "#page.annotation",
"description": "",
"keywords": "",
"section": "",
"tocPath": "",
"tocBookmarks": {}
} -->
