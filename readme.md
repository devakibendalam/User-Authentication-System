# User Authentication System

Built using modern technologies: node.js, express, mongoDB, mongoose.

# User Authentication System
This project implements a comprehensive user authentication system using Node.js with Express and MongoDB. It provides secure user registration, login, and password reset functionalities, along with advanced security features and email capabilities.

## Features

- User registration with input validation
- User login with JWT authentication
- Password reset functionality
- Advanced security measures:
  - Encryption
  - Input sanitization
  - Rate limiting
- Email sending capability
- Image file upload support
- Comprehensive error handling
- Full set of user-related routes

## Technologies Used

- Node.js
- Express.js
- MongoDB
- JSON Web Tokens (JWT)
- mongoose
  

## Installation

1. Clone the repository:
git clone https://github.com/devakibendalam/user-authentication-system.git

2. Navigate to the project directory:
cd user-authentication-system

3. Install dependencies:
npm install

4. Set up environment variables:
Create a `.env` file in the root directory and add the necessary environment variables (database connection string, JWT secret, email service credentials, etc.)

5. Start the server:
npm start

## API Documentation

For detailed API documentation and testing, please refer to our Postman collection:

[Postman API Testing Documentation](https://documenter.getpostman.com/view/27348979/2sA3kYjzu9#b9fd9afa-1628-4484-8ea5-a2509480af83)

## Security Measures
This project implements several security best practices:

- Password encryption
- Input sanitization to prevent injection attacks
- Rate limiting to protect against brute-force attacks
- JWT for secure authentication
- Proper error handling to prevent information leakage

