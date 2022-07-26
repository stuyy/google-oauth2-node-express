# Environment Variables

Create a `.env` file and set the following variables:

```
PORT=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GOOGLE_REDIRECT_URL=
```

_Disclaimer_: This project is not a complete implementation. It only allows the user to login with Google OAuth2, and retrieves the user's Access Token. The access token is used for making authorized requests on behalf of the user's account. e.g: Making an API call to the YouTube Data API would require an access token for some endpoints.
