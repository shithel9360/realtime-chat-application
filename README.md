# Real-time Chat Application

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Node.js](https://img.shields.io/badge/node-%3E%3D14.0-green)
![License](https://img.shields.io/badge/license-MIT-blue)

## Project Overview
A modern real-time chat application with WebSocket support, enabling instant messaging, group chats, file sharing, and end-to-end encryption. Built with Node.js, Socket.io, and React for a seamless user experience across devices.

## Tech Stack
- **Frontend**: React.js, Redux, Material-UI
- **Backend**: Node.js, Express.js
- **Real-time**: Socket.io, WebSocket
- **Database**: MongoDB, Redis (caching)
- **Authentication**: JWT, Passport.js
- **Encryption**: crypto-js, bcrypt
- **File Storage**: AWS S3, Cloudinary
- **Testing**: Jest, React Testing Library, Supertest

## Features
- ✅ Real-time one-on-one messaging
- ✅ Group chat creation and management
- ✅ File and image sharing
- ✅ End-to-end encryption
- ✅ User authentication and authorization
- ✅ Online/offline status indicators
- ✅ Typing indicators
- ✅ Message read receipts
- ✅ Emoji support
- ✅ Message search functionality
- ✅ Push notifications
- ✅ Responsive design for mobile and desktop

## Setup Instructions

### Prerequisites
- Node.js 14.x or higher
- MongoDB
- Redis

### Installation

```bash
# Clone the repository
git clone https://github.com/shithel9360/realtime-chat-application.git
cd realtime-chat-application

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Set up environment variables
cd ../backend
cp .env.example .env
# Edit .env with your configuration

# Start MongoDB and Redis
# Make sure MongoDB and Redis are running

# Run backend server
cd backend
npm run dev

# In a new terminal, run frontend
cd frontend
npm start
```

### Running Tests

```bash
# Backend tests
cd backend
npm test

# Frontend tests
cd frontend
npm test

# E2E tests
npm run test:e2e
```

## Demo

![Demo GIF Placeholder](https://via.placeholder.com/800x400.png?text=Real-time+Chat+Demo)

## API Documentation

View API documentation at `http://localhost:5000/api-docs` when server is running.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - see LICENSE file for details

## Contact

Shithel - [@shithel9360](https://github.com/shithel9360)
