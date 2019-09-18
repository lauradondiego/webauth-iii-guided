- when working with tokens:

* the server

  - produces a token
  - sends token to client

* the client:

  - stores the token
  - sends the token on every request <- to automatically like cookies

  ** notes **

  - npm i jsonwebtoken
  - get the token on insomnia back when you login and copy it without the quotes
  - then go to insomnia and for the get request on users, go to headers, type in authorization then copy the token in the value
  - add config folder and secrets.js file
