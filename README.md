# Jwt
This is an interesting lesson centered around the introduction of JWT authentication.
To create a random access web Token i used : require('crypto').randomBytes(64).toString('hex') ,
Its possible to secure one or a part of your api routes, this is done by adding a verifyjwt middleware to the route involved.   
