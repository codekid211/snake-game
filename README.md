# Snake Game

A classic Snake game implemented in Java with a graphical user interface (GUI) using the Swing library.

## Description

This repository contains a Java implementation of the popular Snake game. The game is played within a window, where the player controls the movement of a snake using the arrow keys. The objective is to navigate the snake to eat cherries that appear randomly on the game board, causing the snake to grow longer with each cherry eaten. The game ends if the snake collides with the walls or its own body.

## Features

- Score and best score tracking
- Pause/resume functionality
- Random cherry spawning
- Cherry image rendering (or fallback to simple oval if image not found)
- Game over screen with option to start a new game
- Smooth snake movement and rendering

## Requirements

- Java Development Kit (JDK) 8 or later
- No external libraries are required

## Installation

1. Clone the repository:
git clone https://github.com/codekid211/snake-game.git

2. Navigate to the project directory:
cd snake-game

## Usage

1. Compile the Java source files:

javac Main.java

2. Run the compiled `Main` class:

java Main


This will launch the Snake game window.

## Project Structure

The project consists of the following Java classes:

- `Main`: The entry point of the application, which creates and displays the game window.
- `Game`: The main class that handles the game logic, rendering, and user input.
- `Snake`: Represents the snake object and manages its movement and growth.
- `Point`: A utility class that represents a 2D point and provides methods for moving and intersecting points.
- `Direction`: An enumeration representing the four possible directions (up, down, left, right) for the snake's movement.
- `GameStatus`: An enumeration representing the different states of the game (not started, running, paused, game over).

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
