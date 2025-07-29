# ♟️ Chess Web App – Multiplayer Chess Game

A web-based multiplayer chess game built using JavaScript, Express, EJS, and Socket.io — supporting real-time gameplay for two players with spectator support.

## 🔧 Features

- Created a two-player online chess game where moves update live for both players
- Used chess.js to enforce standard chess rules like valid moves and player turns
- Set up a simple backend using Express to manage player roles and game state
- Integrated Socket.io to send and receive moves between players in real time
- First two users get white and black pieces, while others can only watch the game
- Added drag-and-drop functionality, with the board flipping for the black player
- Designed the interface using EJS and styled it with CSS
- Deployed the full project on Render for online access

## 📁 Environment Configuration

Create a `.env` file in the root directory and add:

```
PORT=3000
```

## ▶️ Run the App

```bash
npm install
npm start
```

# 🧱 Tech Stack Overview

- 🌐 **Tech Stack:** Node.js, Express.js, EJS, CSS, JavaScript
- ♟️ **Chess Logic:** Powered by the chess.js library
- 💬 **Real-Time Gameplay:** Achieved using Socket.io
- 👥 **Player Management:** First two users join as players (White and Black), others become spectators
- 🖼️ **UI Rendering:** HTML/CSS-based interface with drag-and-drop piece movement
- 🔄 **Live Updates:** Moves are validated and broadcast instantly across connected clients
- 🚀 **Deployment:** Hosted on Render

![Architecture](/assets/architecture.png)

Architecture

![Flowchart](/assets/flowchart.png)

Flowchart