# Chess.io

A simple, real-time online chess game built with Node.js, Express, Socket.io, and Chess.js.

## Features

* **Real-time Gameplay:** Play chess against another player in real-time.
* **Two-Player Support:** Automatically assigns players as White or Black.
* **Move Validation:** Uses `chess.js` to validate moves according to chess rules.
* **Dynamic Board Updates:** The chess board updates for all connected clients as moves are made.

## Technologies Used

* **Node.js:** JavaScript runtime.
* **Express.js:** Web framework for Node.js.
* **Socket.io:** Library for real-time, bidirectional, event-based communication.
* **Chess.js:** JavaScript chess library for move validation, game state, etc.
* **EJS:** Embedded JavaScript templates for rendering dynamic views.

## Getting Started

### Prerequisites

Make sure you have Node.js installed on your system.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url> # Replace with your actual repository URL
    cd chess.io
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```

### Running the Application

1.  **Start the server:**
    ```bash
    node app.js # Or whatever your main server file is named, e.g., server.js, index.js
    ```
    (Based on your provided code, it's likely `app.js` or `index.js`. Assuming `app.js` for this example.)

2.  **Access the game:**
    Open your web browser and navigate to:
    ```
    http://localhost:3000
    ```
    Open another tab or browser window to `http://localhost:3000` to connect as a second player or spectator.
## How to Play
1.  Two players can connect to the server. The first to connect will be assigned as White, and the second as Black.
2.  Players can make moves by dragging and dropping pieces (client-side implementation assumed, not shown in server code).
3.  Spectators can watch the game unfold.
