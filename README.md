# Snake Game
A simple implementation of the classic Snake game using Python and Pygame. Navigate the snake to eat food and grow while avoiding collisions with the walls and itself.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Gameplay Instructions](#gameplay-instructions)
- [Code Overview](#code-overview)
- [Contributing](#contributing)
- [License](#license)

## Features
Classic Snake gameplay mechanics.
Smooth snake movement.
Food generation to grow the snake.
Collision detection with walls and the snake itself.
Restart option after game over.
Score display based on snake length.

## Requirements
To run this game, you need the following:
Python 3.x
Pygame library

## Installation

1. **Clone the repository:**
   git clone https://github.com/yourusername/snake-game.git
   cd snake-game


2. **Install Pygame:**
   You can install Pygame using pip:
   pip install pygame

## How to Run
To start the game, navigate to the project directory in your terminal and run:
python snake_game.py
Make sure to replace `snake_game.py` with the actual name of your Python file if it's different.

## Gameplay Instructions
- Use the arrow keys to move the snake:
**Left Arrow**: Move left
**Right Arrow**: Move right
**Up Arrow**: Move up
**Down Arrow**: Move down
- Eat the white food blocks to grow the snake.
- Avoid running into the walls or the snake itself.
- When you lose, you can press:
**C** to play again
**Q** to quit the game

## Code Overview
The game is structured into the following main functions:
**draw_snake(snake_block, snake_list)**: Draws the snake on the screen using a list of coordinates.
**message(msg, color)**: Displays a message on the screen, typically for game over scenarios.
**display_score(score)**: Renders the current score on the screen.
**gameLoop()**: The main game loop that handles game logic, input, and rendering.

### Main Variables
**snake_block**: The size of each segment of the snake.
**snake_speed**: The speed of the snake's movement.
**snake_List**: A list to keep track of the snake's body segments.
**Length_of_snake**: The current length of the snake.

### Game Logic
1. The snake starts moving in a specified direction based on user input.
2. When the snake eats food, it grows longer, and the score increases.
3. If the snake collides with itself or the screen edges, the game ends.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
