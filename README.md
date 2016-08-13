OAuth2.0-Server-Node.JS-Example
==================

This project is based on [FrankHassanabad/Oauth2orizeRecipes](https://github.com/FrankHassanabad/Oauth2orizeRecipes)

I added a registration page.
And move users data to MongoDB.

You may need to add 

process.env.NODE_TLS_REJECT_UNAUTHORIZED = "0"

in client side, since the certificate is not authorized.
