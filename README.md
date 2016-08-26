# test

a [Sails](http://sailsjs.org) application

steps to start the api-

in CMD

1. npm install 
2. sails lift


basic routes for authentication are:

* http://localhost:1337/signup
POST request body(key:value):
1. email : your email
2. password : password 
3. confirmPassword : password 

* http://localhost:1337/login
POST request body(key:value):
1. email : your email
2. password : password 

until passing the login token in header as the Authorization - Bearer LOGIN_TOKEN , access won't be granted by the api.

then simple routes like 

http://localhost:1337/user
http://localhost:1337/user/create 

will work 

use this link to understand more about the authentication done in the project- https://github.com/saviogl/sails-hook-jwt-auth
