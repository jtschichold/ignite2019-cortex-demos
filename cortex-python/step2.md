To access the Cortex API, the API client needs an _access token_.  

There are 2 ways to grab an access token:
- Full applications receive an access token when the user completes the OAuth2 authorization process. Check pancloud documentation for more details: [https://pancloud.readthedocs.io/en/latest/guides/credentials.html#oauth-2-0-credentials](https://pancloud.readthedocs.io/en/latest/guides/credentials.html#oauth-2-0-credentials)
- API Explorer provides a Developer Token mechanism. Extremely useful to get you started with scripts without building a full app.

Grab your developer token from your API Explorer following the instructions here: [https://pancloud.readthedocs.io/en/latest/guides/credentials.html#developer-tokens](https://pancloud.readthedocs.io/en/latest/guides/credentials.html#developer-tokens)

Set the environment variable `PAN_DEVELOPER_TOKEN` with the developer token: `export PAN_DEVELOPER_TOKEN=<your token>`{{copy}}
