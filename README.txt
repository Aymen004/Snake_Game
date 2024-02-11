# Snake Game

This is a simple implementation of the classic Snake game using JavaScript.

## Features

- The game board is displayed in the browser.
- The snake is controlled using the arrow keys or on-screen controls.
- The game keeps track of the current score and high score.
- The high score is stored in the local storage and persists across sessions.
- The game ends when the snake hits the wall or its own body.

## How to Run

1. Clone this repository.
2. Open `index.html` in your browser.

## Code Overview

The game logic is contained in `script.js`. Here's a brief overview of what each part of the code does:

- `playBoard`, `scoreElement`, and `highScoreElement` are DOM elements that display the game board, current score, and high score respectively.
- `gameOver`, `foodX`, `foodY`, `snakeX`, `snakeY`, `velocityX`, `velocityY`, `snakeBody`, `setIntervalId`, and `score` are variables that store the current state of the game.
- `updateFoodPosition` is a function that sets `foodX` and `foodY` to a random position on the board.
- `handleGameOver` is a function that ends the game and reloads the page.
- `changeDirection` is a function that changes the direction of the snake based on the arrow key pressed.
- `initGame` is a function that updates the game state and redraws the game board every 100 milliseconds.
- The last three lines of the code set up the initial state of the game and start the game loop.

## Styling

The game's visual appearance is defined in `style.css`. This includes the layout of the game board, the colors of the snake and food, and the font used for the score display. The CSS also includes media queries to make the game responsive, so it looks good on both desktop and mobile devices.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

