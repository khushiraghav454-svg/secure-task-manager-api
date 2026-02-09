# Secure Task Manager API

A secure REST API built using Node.js, Express and MongoDB. It uses JWT authentication to protect APIs and ensures that users can manage only their own tasks.

## Features
- User registration and login
- JWT based authentication
- Protected routes
- Create, read, update and delete tasks
- User based authorization

## Tech Stack
- Node.js
- Express.js
- MongoDB & Mongoose
- JSON Web Token (JWT)
- bcrypt
- dotenv

## Setup
Create a `.env` file in the root folder:

PORT=5000  
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_jwt_secret  

Install and run the project:

npm install  
npm start  

## API Endpoints

Auth APIs  
- POST /api/auth/register  
- POST /api/auth/login  

Task APIs (Protected)  
- POST /api/tasks  
- GET /api/tasks  
- PUT /api/tasks/:id  
- DELETE /api/tasks/:id  

## Postman
Postman collection is included in the project:

postman/Secure-Task-Manager.postman_collection.json  

Postman environment variables:

baseUrl = http://localhost:5000  
token = JWT token received after login  

## Branch Flow
dev → stage → main

## Author
Khushi Raghav
