## Google OAuth Tokens
Authorization Code Starts With: `4/0A...`

Access Token Starts With: `ya29.a0...`

**Based off scope of token use: https://www.googleapis.com/oauth2/v1/userinfo?access_token=ya29.a0...**

See : https://developers.google.com/oauthplayground/

## Microsoft OAuth
Authorization are either JWTs and as such start with: `eyJ0...` OR start with `EwBwA8...`

Use tokens:
```
GET /v1.0/me HTTP/1.1
Host: graph.microsoft.com
Pragma: no-cache
Cache-Control: no-cache
Sec-Ch-Ua: "Chromium";v="103", ".Not/A)Brand";v="99"
Authorization: Bearer {YOUR TOKEN}
```
