# Greddit

## Overview

Gredit is a MERN (MongoDB, Express.js, React, Node.js) stack application inspired by Reddit. It includes features such as user authentication, post creation, commenting, upvoting/downvoting, and more. The application is containerized using Docker for easy deployment and scaling.

## Features

1. **User Authentication**
    - Registration
    - Login
    - JWT for session management
    - Password encryption

2. **User Profiles**
    - View and edit profile
    - Profile picture upload

3. **Posts**
    - Create, read, update, delete
    - Upvote/downvote
    - Commenting

4. Other features similar to Reddit.

## Installation

### Prerequisites
- Node.js
- MongoDB
- Docker

### Backend Setup

1. Install dependencies:
    ```bash
    cd backend
    npm install
    ```

2. Create a `.env` file in the `backend` directory and add the following:
    ```env
    PORT=5000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

3. Start the backend server:
    ```bash
    npm run dev
    ```

### Frontend Setup
1. Navigate to the `frontend` directory:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the frontend development server:
    ```bash
    npm start
    ```

### Docker Setup
1. Build and run the Docker containers:
    ```bash
    docker-compose up --build
    ```

