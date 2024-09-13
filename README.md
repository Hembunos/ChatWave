
# ChatWave - MERN Chat Application

ChatWave is a real-time chat application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It enables users to send and receive messages instantly and includes features such as group chats, user authentication, and message notifications.

## Features

- **Real-time Messaging:** Communicate instantly with other users.
- **Group Chats:** Create and join group chats to interact with multiple users.
- **User Authentication:** Secure login and registration using JWT.
- **Notifications:** Receive real-time notifications for new messages.
- **Responsive Design:** Compatible with both desktop and mobile devices.

## Tech Stack

- **Frontend:** React.js, Chakra UI, Socket.io-client
- **Backend:** Node.js, Express.js, Socket.io
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Styling:** Chakra UI, Emotion

## Installation

To set up a local copy of ChatWave, follow these steps:

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Hembunos/chatwave.git
   cd chatwave
   ```

2. Navigate to the backend folder:
   ```bash
   cd backend
   ```

3. Install backend dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the `backend` directory and add your environment variables:
   ```env
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   PORT=your_port
   NODE_ENV=your_node_env
   ```

5. Start the backend server using Nodemon:
   ```bash
   npm run server
   ```

### Frontend Setup

1. Navigate to the frontend folder:
   ```bash
   cd ../frontend
   ```

2. Install frontend dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm start
   ```

4. Open your browser and go to `http://localhost:3000` to view the application.

## Usage

1. Register a new account or log in with an existing account.
2. Create a new chat or join an existing chat.
3. Start sending messages to other users or groups.
4. Receive real-time notifications for new messages.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add your feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please contact [hembu250@gmail.com](mailto:hembu250@gmail.com).
