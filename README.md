# xMy Chat Application

## Prerequisites
- Node.js
- npm

## Getting Started

This project consists of a `client` (React/Vite) and `server` (Node/WebSocket). You must run **both** for the application to work correctly.

### 1. Start the Server (WebSocket)
The server handles real-time chat connections.

Open a terminal and run:

```bash
cd server
npm install
npm run dev
```

The server will listen on `ws://localhost:4000`.

### 2. Start the Client (React)
The client is the frontend user interface.

Open a **new** terminal window and run:

```bash
cd client
npm install
npm run dev
```

The client will start on `http://localhost:5173` (or similar).

## Troubleshooting
- **WebSocket Connection Failed**: Ensure the server is running on port 4000. If you see "WebSocket Disconnected" or "WebSocket not ready" in the browser console, the server is likely not running or crashed.
