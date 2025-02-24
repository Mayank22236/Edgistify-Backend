# Backend API

This is a Node.js backend application that includes user authentication, database integration with MongoDB, and environment configuration.

## Features
- User authentication with JWT
- Secure password hashing using bcrypt.js
- CORS enabled for cross-origin requests
- Environment variable support using dotenv
- MongoDB integration with Mongoose
- Automatic server restart during development using Nodemon

## Installation and Setup

### 1. Clone the Repository
```sh
git clone <your-repo-url>
cd backend

Install Dependencies
npm install

Create a .env file in the root directory and add your environment variables. Example:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Start the Server
npm start

