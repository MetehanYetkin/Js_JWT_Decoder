
# Json Web Token(JWT)  Decoder 
![images](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTiyOk8qnR5SEwPJ2ccOIYxdhUgDeO2ioKPZA&usqp=CAU)

##  What is JWT Token?

JWT(JSON Web Token) is a recommended standard JSON object that holds all user data signed using private key or public/private key. JWT tokens are secured due to algorithms like (HMAC, RSA) used to sign them and also JWT is small in size which helps in transmission. These two reasons make the JWT token attractive for modern web and mobile application.
With client-server architecture, usually the client receives the JWT token from the server and keeps it locally (in local storage/session storage). The client will place the JWT token in the header of each request and forward it to the server to authorize a request.

 - When I wanted to use the token I created on the backend side of this structure, which I also use in many of my projects, I decoded it with the 'atob' function available in javascript and used the data, but since 'atob' does not work in some browsers, I wanted to perform my own JWT token decoder algorithm with pure string functions.

