# pkce-spa-js
PKCE in a Single Page App with Plain Vanilla JS

## How to Set-up
npm run serve-https -> https://localhost
npm start -> http://localhost:3000

## Note
If running the server in a different port, then the redirect uri 
has to be changed accordingly in the code in the below section
<code>
    var config = {
    client_id: "r2F2Qd6ZJKtpctTggacA8Ml1WUXDJSB7",
    redirect_uri: "https://localhost",
    authorization_endpoint: "https://healthexpress.au.auth0.com/authorize",
    token_endpoint: "https://healthexpress.au.auth0.com/oauth/token",
    logout_endpoint: "https://healthexpress.au.auth0.com/v2/logout",
    requested_scopes: "openid profile email"
};
</code>
## Blog
https://pradheepa.medium.com/pkce-an-introduction-dcccfce86dc
https://pradheepa.medium.com/pkce-introduction-part-ii-b591e0ad736d

### References
https://github.com/auth0/spa-pkce
https://github.com/aaronpk/pkce-vanilla-js
https://web-in-security.blogspot.com/2017/01/pkce-what-cannot-be-protected.html
https://www.freecodecamp.org/news/how-to-get-https-working-on-your-local-development-environment-in-5-minutes-7af615770eec/