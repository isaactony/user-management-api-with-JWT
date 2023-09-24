# User Management API with JWT
This repository contains a simple User Management API implemented using Node.js, Express, MongoDB, and JSON Web Tokens (JWT). The API provides endpoints for user registration, login, and accessing protected routes that require authentication.
# Installation      
Clone the repository:   
```git clone https://github.com/isaactony/user-management-api-with-JWT.git```        
# Install the dependencies:        
```       
cd user-management-api-with-JWT         
npm install            
```             
# Set up the environment variables:          
    
- Create a .env file in the project root directory.
- Define the following variables in the .env file:
- PORT - The port number on which the API will run (default is 5000).
- MONGODB_URI - The URI of your MongoDB database.
- JWT_SECRET - The secret key for JWT token generation and verification.

# Start the API:
```   
npm start 
The API will be available at http://localhost:5000 (or the specified port).
```

# Usage
### The API exposes the following endpoints:

- POST /users: Register a new user.

- GET /users: Get a list of users.

- GET /users/:userId: Get user details by user ID.

- PATCH /users/:userId: Update user details by user ID.

- DELETE /users/:userId: Delete a user by user ID.


To access the protected routes, you need to include the JWT token in the request headers:


# Technologies Used
- Node.js
- Express
- MongoDB
- JSON Web Tokens (JWT)
- Docker


# License
- This project is licensed under the MIT License.


# Developer
Isaac Tonyloi



