# jwt-authentication-api
# JWT Authentication & Authorization API
# Internship - Prodigy InfoTech

## Overview
This project is a secure REST API built using Node.js, Express.js, MongoDB Atlas, JWT (JSON Web Token), and bcrypt. It provides user registration, login, authentication, and role-based authorization.

## Technologies Used
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT (jsonwebtoken)
- bcryptjs
- Dotenv
- Postman

## Features
- User Registration
- User Login
- Password Hashing using bcrypt
- JWT Token Generation
- Protected Routes
- User Authentication
- Role-Based Authorization
- MongoDB Atlas Integration

## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install dependencies

```bash
npm install
```

3. Create a .env file

```env
MONGO_URI=your_mongodb_connection_string
PORT=3000
JWT_SECRET=your_secret_key
```

4. Start the server

```bash
node index.js
```

## API Endpoints

### Register User
POST /register

### Login User
POST /login

### Protected Profile Route
GET /profile

### Admin Route
GET /admin

## Sample Registration Data

```json
{
  "name": "Sreedev",
  "email": "sreedev@gmail.com",
  "password": "123456",
  "role": "user"
}
```

## Sample Login Data

```json
{
  "email": "sreedev@gmail.com",
  "password": "123456"
}
```

## Output

- User registration with encrypted passwords.
- Secure login using JWT authentication.
- JWT token generated after successful login.
- Protected routes accessible only with valid tokens.
- Role-based access control implemented.

## Author

Sreedev Sreekumar
