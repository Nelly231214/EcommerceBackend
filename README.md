# EcommerceBackend

## Features
 * User registration and login
 * Authentication via JWT
 * MongoDB database

 ## Getting Started
 To test the application

* Register on https://www.mongodb.com/atlas/database
* Create your free shared database and choose a username and password for it
* Add your username and password to the .env file (you need to create your .env file in the root of the project)
* Example MONGO_URI="mongodb+srv://username:password@cluster0.nfa40se.mongodb.net/?retryWrites=true&w=majority"
* Choose a random string as JWT secret or generate it in your terminal
* Copy it and place in in your .env file
* Example TOKEN_SECRET="yourrandomlygeneratedsecret" 
* Start the application
```nodemon index.js```

* Register via http://localhost:5000/api/auth/register with username, email, and password in the body as JSON format via Postman or any alternatives

* Login via http://localhost:5000/api/auth/login with the same email and password
* Your response should have a JSON token
* Place it inside the Authentication tab Bearer Token
* Make a request to http://localhost:5000/api/product
* If you get 200 OK as a result, everything was successul

## Author