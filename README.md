## Authentification vs Authorization

- Authentification: credentials that prove user is who they say they are (most commonly username and psswrd)
- Authorization: what user has access to when logged in

## Devise

- gem that helps with authentification and authorization
- ability to create user
- user can log in and have access to certain parts of application
- bank analogy

## JWT (js web tokens)

- token handed from backend to frontend
- tells our app a user is logged in (session) and authenticated
- credit card analogy

## future ref

- update url to deployed frontend link in config/initializers/cors.rb: origins 'http://localhost:3001'
- jws_secret_key will not save
