# Platform v0

A first test on handling Sails web framework with the following features :
* user authentication stored on MySQL

To install you need node js and npm, as well as MySQL with credentials :
* username : root
* password : password

Run the following command after cloning the project :

`npm install`

`sails lift`

I've followed theses tutorials :

* [Starting with Sails](https://www.smashingmagazine.com/2015/11/sailing-sails-js-mvc-style-framework-node-js/)
* [Using passport](https://github.com/sails101/using-passport)

## Authentication

To use the tutorial, you need to check out the files :
* /api/policies/sessionAuth.js
* /api/responses/login.js
* /api/responses/unauthorized.js
