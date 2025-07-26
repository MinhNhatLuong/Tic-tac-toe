# React Tic-Tac-Toe

A modern implementation of the classic Tic-Tac-Toe game built with React and Vite.

![Game Screenshot](public/game-logo.png)

## Features

- 🎮 Interactive gameplay for two players
- 📝 Editable player names
- 🔄 Game state tracking and move history
- 🏆 Automatic winner detection
- 🎨 Attractive animations and styling
- 📱 Responsive design

## Technologies Used

- React 19
- Vite 4
- CSS3 with animations
- Modern JavaScript (ES6+)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```sh
git clone https://github.com/yourusername/tic-tac-toe.git
```

2. Install dependencies
```sh
npm install
```

3. Start the development server
```sh
npm run dev
```

4. Open http://localhost:5173 in your browser

## How to Play

1. Players take turns clicking on empty squares to place their symbol (X or O)
2. Edit player names by clicking the "Edit" button next to each player
3. The game automatically detects when a player wins or when there's a draw
4. Click "Rematch" to start a new game

## Project Structure

```
tic-tac-toe/
├── public/								# Static assets
├── src/
│   ├── components/						# React components
│   ├── assets/							# Images and other assets
│   ├── App.jsx							# Main application component
│   └── index.jsx						# Application entry point
├── index.html							# HTML template
└── package.json						# Project dependencies and scripts
```

## Build

To create a production build:

```sh
npm run build
```

The built files will be in the `dist` directory.

## Acknowledgments

- Built as part of a React learning journey
- Inspired by the classic Tic-Tac-Toe game