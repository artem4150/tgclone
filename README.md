# Simple WebRTC Voice Chat

This project provides a minimal example of a group voice chat similar to a Discord voice room. The server is built with **Node.js**, **Express**, and **Socket.IO** for signaling. The client is a single HTML page that connects users via WebRTC.

## Running the project

1. Install dependencies:
   ```bash
   npm install --prefix server
   ```
2. Start the server:
   ```bash
   npm start --prefix server
   ```
3. Open `http://localhost:3000` in multiple browser windows or devices and click **Join Room** to start the call.

Users join the same `main` room by default. Audio from each participant will play in the browser when others join.
