# Flappy Bird Clone

A simple Flappy Bird clone created using HTML and JavaScript. The game features basic mechanics where the player controls a bird and must navigate through pipes to score points. The game includes collision detection and score tracking.

## Features

- **Start the Game**: The game starts automatically once the page loads.
- **Control the Bird**: Press the space bar to make the bird jump.
- **Collision Detection**: The game detects collisions with pipes and the canvas edges.
- **Score Tracking**: The score increases as the bird successfully navigates through the pipes.

## How to Play

1. **Start the Game**: The game starts automatically once the page loads.
2. **Control the Bird**: Press the space bar to make the bird jump.
3. **Objective**: Navigate the bird through the pipes without colliding with them or the canvas edges.
4. **Game Over**: The game reloads when a collision is detected.

## Game Mechanics

- **Bird Movement**: The bird moves down continuously due to gravity. Pressing the space bar makes the bird jump.
- **Pipes**: Pipes move from right to left. New pipes are added periodically.
- **Score**: The score increases each time the bird successfully navigates through a set of pipes.

## Code Structure

- **HTML**: Defines the structure of the game, including the canvas element.
- **CSS**: Provides basic styling for the canvas and game elements.
- **JavaScript**: Contains the game logic, including:
  - Initialization of canvas and game variables
  - Functions for drawing the bird and pipes
  - Collision detection
  - Score updates

## Usage

To run the game:

1. Save the provided HTML code into a file named `flappy-bird.html`.
2. Open the file in a web browser to start playing.
