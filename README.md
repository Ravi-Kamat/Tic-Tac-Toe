# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game implemented using React. It allows two players to take turns and play the classic game of Tic-Tac-Toe in a web browser.

## Features

- **Two-player mode:** Players can take turns playing the game on the same device.
- **Responsive design:** The game is responsive and works on different screen sizes.
- **Winning logic:** The game detects and announces the winner or if the game ends in a draw.
- **Restart game:** Players can restart the game at any time.

## Demo

[Link to live demo](#) (replace with your live demo link if available)

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://git@github.com:Ravi-Kamat/Tic-Tac-Toe.git
   cd tic-tac-toe-react
   ```

### Install dependencies:

npm install

### Start the development server:

npm start

## Usage

Click on a cell to place your marker (X or O).
Players alternate turns until there is a winner or the game ends in a draw.
The game will announce the result at the end.
Click the "Restart Game" button to start a new game.

## Project Structure

tic-tac-toe-react/
├── public/
│ ├── index.html
│ └── ...
├── src/
│ ├── components/
│ │ ├── Card.js
│ │ ├── Grid.js
│ │ └── Icon.js
│ ├── helpers/
│ │ └── CheckWinners.js
│ ├── App.js
│ ├── index.js
│ └── ...
├── .gitignore
├── package.json
├── README.md
└── ...

## Components

App.js: The main component that renders the Game component.
Game.js: Manages the state of the game and contains the game logic.
Board.js: Renders the game board.
Cell.js: Renders a single cell on the board.

## Helpers

CheckWinners.js: Contains helper functions for game logic, such as checking for a winner and determining valid moves.
