# Realtime Chat App

A full-stack real-time chat application built using the MERN stack with Socket.IO for real-time messaging, Tailwind CSS for a responsive design, and JWT for secure authentication.

## Live Demo
[Visit the live site](https://realtime-chat-app-9g3z.onrender.com) 
## Features
- **Responsive UI**: Designed using Tailwind CSS and DaisyUI for seamless mobile and desktop compatibility.
- **Real-Time Messaging**: Instant communication enabled with Socket.IO, including live user status.
- **Notifications**: Real-time delivery notifications for messages.
- **Message Storage**: Messages are stored and retrieved efficiently using MongoDB.
- **Deployment**: The app is deployed on Render with continuous integration.
- **Authentication**: Secure user login and registration with JWT authentication.
- **User Status**: Online/offline indicators implemented via WebSocket connections.

## Tech Stack
- **Frontend**: React.js, Tailwind CSS, DaisyUI
- **Backend**: Node.js, Express.js, Socket.IO
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Deployment**: Render

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/rohit-2002/Realtime-Chat-App.git
   cd Realtime-Chat-App
2. Install dependencies for both frontend and backend:
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
3. Create a .env file in the backend directory with the following variables:
   ```bash
   MONGODB_URI=...
   PORT=5001
   JWT_SECRET=...
   CLOUDINARY_CLOUD_NAME=...
   CLOUDINARY_API_KEY=...
   CLOUDINARY_API_SECRET=...
   NODE_ENV=development
4. Start the backend server:
   ```bash
   cd backend
   npm run dev
5. Start the frontend server:
   ```bash
   cd frontend
   npm run dev
6. Build the app
   ```bash
   npm run build
7. Open the app in your browser at http://localhost:5073.
  
