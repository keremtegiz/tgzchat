# tgzchat - Real-Time Chat Application

## Overview
**tgzchat** is a simple real-time chat application built with Node.js, Express, and Socket.io. It allows users to send messages and receive live feedback about who is currently typing. The application features a basic frontend where users can input their names and send messages to the chat room.

## Features
- Real-time communication using Socket.io
- Broadcast chat messages to all connected users
- "Typing" notification when a user is composing a message
- Simple and clean user interface

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express, Socket.io
- **Socket.io**: Real-time, bidirectional communication between clients and server

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/keremtegiz/tgzchat.git
cd tgzchat

npm install
node server.js
nodemon server.js
http://localhost:3000
