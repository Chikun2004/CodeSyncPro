# Real-Time Collaborative Editor

A real-time collaborative text editor built with Node.js, Express.js, React.js, and WebSocket.

## Features

- Real-time text synchronization
- Multiple user cursors
- Document version control
- User roles (editor/viewer)
- Conflict resolution

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Real-time Communication**: WebSocket (ws)
- **State Management**: React Context API

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install server dependencies:
   ```bash
   cd server
   npm install
   ```
3. Install client dependencies:
   ```bash
   cd ../client
   npm install
   ```

### Running the Application

1. Start the server:
   ```bash
   cd server
   npm run dev
   ```
2. Start the client:
   ```bash
   cd client
   npm start
   ```

The application will be available at `http://localhost:3000`

## Usage

1. Open the application in multiple browser windows
2. Create or join a document using the document ID
3. Start collaborating in real-time!

## License

MIT
