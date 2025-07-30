# Snake Game

## Overview

This is a classic Snake game implemented in Python using the Turtle graphics library. The player controls a snake that moves around the screen, consuming food to grow longer while avoiding collisions with the walls and its own body. The game keeps track of the player's score, which increases with each piece of food eaten.

## Features

- **Snake Movement**: Control the snake using arrow keys (Up, Down, Left, Right) to navigate the game area.
- **Food Collection**: The snake grows longer each time it eats the red circular food, which spawns randomly on the screen.
- **Score Tracking**: A scoreboard displays the current score, incrementing with each food consumed.
- **Game Over**: The game ends if the snake hits the walls or collides with itself, displaying the final score on a dark red background.

## Files

- `Main.py`: The main game script that initializes the game window, sets up the snake, food, and scoreboard, and handles the game loop and user input.
- `snake.py`: Contains the `Snake` class, which manages the snake's creation, movement, growth, and direction changes.
- `food.py`: Defines the `Food` class, responsible for creating and randomly positioning the food on the screen.
- `Scoreboard.py`: Implements the `Board` class to display and update the score and show the game-over message.

## How to Play

1. Run `Main.py` using a Python environment with the Turtle library installed.
2. Use the arrow keys to control the snake's direction:
   - **Up Arrow**: Move up
   - **Down Arrow**: Move down
   - **Right Arrow**: Move right
   - **Left Arrow**: Move left
3. Guide the snake to eat the red food to increase your score and grow the snake.
4. Avoid hitting the walls (beyond ±375 coordinates) or the snake's own body.
5. The game ends when a collision occurs, displaying "Game Over!" and the final score.
6. Click the screen to exit the game.

## Requirements

- Python 3.x
- Turtle graphics library (included with standard Python installations)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/snake-game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd snake-game
   ```

3. Run the game:

   ```bash
   python Main.py
   ```

## Gameplay Notes

- The game window is an 800x800 pixel black canvas.
- The snake moves continuously, updating every 0.1 seconds.
- Food appears as a small red circle at random positions within the game boundaries.
- The score is displayed at the top center of the screen.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license terms.
