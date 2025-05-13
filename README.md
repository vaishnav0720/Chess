# Chess Multiplayer Web App

A real-time multiplayer chess game built with Node.js, Express, Socket.io, and chess.js.

## Features

- Real-time chess gameplay between two players
- Spectator mode for additional users
- Drag-and-drop chess pieces
- Responsive chessboard UI (Tailwind CSS)
- Move validation and turn enforcement

## Demo

1. Install dependencies:
    ```sh
    npm install
    ```
2. Start the server:
    ```sh
    node app.js
    ```
3. Open your browser at [http://localhost:3000](http://localhost:3000)
4. Open a second browser window or tab to play as the other player or as a spectator.

## Project Structure

- **app.js**: Main server file, handles game logic and socket connections.
- **package.json**: Project metadata and dependencies.
- **public/js/chessgame.js**: Client-side chess logic and UI rendering.
- **views/index.ejs**: Main HTML template for the chessboard.

```
d:\Web-Devlopment\Project\Chess
│   app.js
│   package.json
│   README.md
│
├───public
│   └───js
│       └───chessgame.js
│
└───views
    └───index.ejs
```