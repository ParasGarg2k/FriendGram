
# FRIENDGRAM

This is a **Real-Time Chat Application** built using **JavaScript**, **React**, and **Node.js** with **Socket.io** for real-time communication. The application allows users to chat in different rooms, with real-time message delivery, user authentication, and a simple, responsive UI.

## Features
- Real-time messaging with **Socket.io**.
- User authentication (register and login).
- Private and group chat functionality.
- Responsive user interface built with **React**.
- Chat rooms and direct messaging.
- Backend powered by **Node.js** and **Express.js**.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/parasgarg2k/FriendGram.git
   ```

2. Navigate into the project directory:
   ```bash
   cd FriendGram
   ```

### Backend Setup:

3. Navigate into the backend directory:
   ```bash
   cd backend
   ```

4. Install the required dependencies:
   ```bash
   npm install
   ```

5. Create a `.env` file in the `backend` directory and configure the following environment variables:
   ```
   PORT=5000
   MONGO_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret_key>
   ```

6. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup:

7. Navigate into the frontend directory:
   ```bash
   cd ../frontend
   ```

8. Install the required dependencies:
   ```bash
   npm install
   ```

9. Start the React application:
   ```bash
   npm start
   ```

10. Open your browser and navigate to `http://localhost:3000/` to access the chat application.

## Usage

1. **Register** as a new user or **login** if you already have an account.
2. Create chat rooms or join existing ones.
3. Chat with other users in real time.
4. Use private messaging for one-on-one conversations.

## Technologies Used

- **Frontend**: React.js, JavaScript, CSS
- **Backend**: Node.js with Express.js
- **Real-Time Communication**: Socket.io
- **Database**: MongoDB (Mongoose ORM)
- **Authentication**: JWT (JSON Web Token)


## Authentication

The app uses **JWT (JSON Web Token)** for user authentication. After logging in, the user receives a token, which must be sent in the `Authorization` header for protected routes. Example:

```bash
Authorization: Bearer <your_token_here>
```
