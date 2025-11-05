Replace in Manifest keys "web" and "spa" to the following values:

```json
{
  "web": {
		"homePageUrl": null,
		"logoutUrl": null,
		"redirectUris": [
			"https://site-250101.powerappsportals.com"
		],
		"implicitGrantSettings": {
			"enableAccessTokenIssuance": false,
			"enableIdTokenIssuance": true
		},
		"redirectUriSettings": [
			{
				"uri": "https://site-250101.powerappsportals.com",
				"index": null
			}
		]
	},
	"spa": {
		"redirectUris": [
			"https://127.0.0.1:8001/*",
			"https://127.0.0.1:8002/*",
			"https://site-250101.powerappsportals.com/page-not-found/",
			"https://site-250101.powerappsportals.com/_layout/tokenhtml"
  	]
  }
}
```
