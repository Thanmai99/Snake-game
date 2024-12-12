# Snake game
This project implements a **SnakeMania** game using HTML, CSS, and JavaScript. It creates an interactive game where the player controls a snake that moves around the screen to eat food, growing in length with each item consumed. The game includes features like scoring, a high score tracker, collision detection, and sound effects.

## How It Works
- The **snake** is represented as a series of blocks that move in a grid. The player controls the direction of the snake using arrow keys.
- The **food** appears at random positions on the grid. When the snake's head collides with the food, the snake grows longer, and the score increases.
- The **game ends** when the snake collides with itself or the wall. The current score is displayed, and the player is given an option to restart.
- The game **tracks the high score** by saving it in `localStorage`, so it persists across page reloads.
- **Sound effects** are played during the game for actions like eating food, moving, and game over.

## Code Overview
The core logic is found in several key functions:

- `isCollide(snake)` : Checks if the snake collides with itself or the boundaries of the game board.
- `gameEngine()` : Updates the game state, including snake movement, food regeneration, score updates, and collision checks.
- `main(ctime)` : Controls the game loop, ensuring that the game updates at the correct speed.
- `keyboard controls (keydown)`: Handles the player's input for controlling the snake's movement.

## Usage
1. Clone this repository
