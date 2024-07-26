# SnakesWithFARHA

SnakesWithFARHA is a modern take on the classic Snake game, built using Python and Pygame. Navigate the snake to eat the food, grow in length, and avoid collisions. This project serves as a fun way to learn and demonstrate the basics of game development with Pygame.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Game](#running-the-game)
- [How to Play](#how-to-play)
- [Features](#features)
- [Customization](#customization)
- [Files](#files)
- [License](#license)

## Getting Started

### Prerequisites

- Python 3.x
- Pygame library


You can install Pygame using pip:

```sh
pip install pygame
```


### Installation

1. Clone the repository:

```sh
git clone https://github.com/Farhaaaaaaa/SnakesWithFarha.git
```

2.Ensure all dependencies are installed:
```sh
pip install -r requirements.txt
```

### Running the Game

Run the script using Python:

```sh
python snakeswithfarha.py
```

## How to Play

- **Movement**: Use the arrow keys to move the snake.
  - Right arrow key: Move right
  - Left arrow key: Move left
  - Up arrow key: Move up
  - Down arrow key: Move down
- **Start Game**: Press the `Space Bar` at the welcome screen.
- **Objective**: Eat the red food squares to gain points and grow the snake.
- **Avoid**: Do not run into the walls or the snake's own body, as this will end the game.
- **Score**: Your current score and high score are displayed at the top of the game window.

## Features

- **Welcome Screen**: Interactive welcome screen with instructions.
- **Score Tracking**: Real-time score updates with high score tracking.
- **Game Over Screen**: Option to restart the game after a game over.
- **Responsive Controls**: Smooth snake movement with arrow keys.
- **High Score Storage**: High score is saved in a file and persists between game sessions.

## Customization

You can customize various aspects of the game:

- **Snake Speed**: Adjust the `init_velocity` variable in the `gameloop` function.
- **Snake Size**: Change the `snake_size` variable.
- **Food Position**: Modify the `food_x` and `food_y` generation logic for more complexity.
- **Colors**: Customize the colors by changing the RGB values of `white`, `red`, `black`, etc.
- **Screen Dimensions**: Adjust `screen_width` and `screen_height` for different window sizes.
- **Fonts**: Change the font style and size by modifying the `font` variable.

## Files

- `snakeswithfarha.py`: Main game script.
- `hiscore.txt`: File to store the highest score. This file is automatically created if it doesn't exist.
- `requirements.txt`: List of dependencies for easy installation. (You may need to create this file with the necessary dependencies listed, such as `pygame`.)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

