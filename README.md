# Social-Connect MERN Application

Welcome to the MERN Social Media Application! This README provides an overview of the project, including setup instructions, features, and technologies used. This application is built using the MERN stack (MongoDB, Express.js, React, and Node.js) and provides a fully functional social media platform.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)


## Features

- User authentication and authorization
- Create, read, update, and delete posts
- Follow and unfollow users
- Like and comment on posts
- User profiles with bio and profile picture

## Technologies Used

- **Frontend:**
  - React
  - Redux (for state management)
  - Axios (for API requests)

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB (with Mongoose for object modeling)
  - JWT (for authentication)
  - Bcrypt.js (for password hashing)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed
- MongoDB installed and running

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/himanshuarya3110/DevConnect.git
   cd DevConnect
   ```

2. **Install dependencies:**

   For the backend:

   ```bash
   cd server
   npm install
   ```

   For the frontend:

   ```bash
   cd ../client
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the `backend` directory and add the following variables:

   ```plaintext
   PORT=your_port
   MONGODB_CONNECTION=your_mongodb_connection_string
   JWTKEY=your_jwt_secret
   ```

4. **Run the application:**

   In the `backend` directory, start the backend server:

   ```bash
   npm run dev
   ```

   In the `frontend` directory, start the React development server:

   ```bash
   npm start
   ```

   The application should now be running on `http://localhost:3000` (frontend) and `http://localhost:5000` (backend).
