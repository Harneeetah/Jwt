# Jwt
This is an interesting lesson centered around the introduction of JWT authentication.
To create a random access web Token i used : require('crypto').randomBytes(64).toString('hex') ,
Its possible to secure one or a part of your api routes, this is done by creating a verifyjwt middleware and adding it to the route(s) involved.   
