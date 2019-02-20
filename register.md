# Registration

One is required to register in-order to use the API . Once Registration is successful,
 Please contact support desk at dennis.monari@hotmail.com to get your account activated.


### JSON representation

 `POST /api/auth/signup`.

<!-- { "blockType": "resource",
"@type": "author",
"optionalProperties": [] } -->
```json
{
	"name": "test",
	"email":"test@dtest.com",
	"password":"password",
	"password_confirmation": "password"
	
}
```

200 indicates that the request has succeeded.

```json
{
    "message": "Successfully created user!"
}
```
### Properties

| Property | Type | Description |
|:---------|:-----|:------------|
| **name**   | String | Registrant's name. |
| **email** | email | The email address. |
| **password** | String | the password. |
| **password_confirmation** | String | the password confirmation. |

<!-- {
"type": "#page.annotation",
"description": "",
"keywords": "",
"section": "",
"tocPath": "",
"tocBookmarks": {}
} -->
