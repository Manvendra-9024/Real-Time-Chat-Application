# Real-Time Chat Application

## Overview
A full-stack real-time chat application supporting private messaging, group rooms, and message history.

## Tools & Technologies
- **Node.js** – Backend server
- **Python** – Bot integration and analytics scripts
- **MySQL** – Message persistence and user data
- **Encryption** – TLS in transit, AES for stored messages

## Project Structure
```
real_time_chat_application/
├── server/
│   ├── index.js
│   ├── socket/
│   └── routes/
├── client/
│   └── public/
├── database/
│   └── schema.sql
├── analytics/
│   └── chat_stats.py
└── README.md
```

## Features
- WebSocket-based real-time messaging (Socket.io)
- User authentication with JWT
- Private and group chat rooms
- Message history with MySQL persistence
- End-to-end encrypted private messages
- Online/offline status indicators

## Setup
```bash
npm install
node server/index.js
```
