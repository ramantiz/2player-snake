# Two-Player Snake Game

## Overview

This is a basic implementation of a two-player Snake game using HTML, CSS, and JavaScript. The game allows two players to control their snakes simultaneously and compete to eat food, which increases their respective scores.

## Features

- **Two-Player Mode**: Players can control two different snakes.
- **Food Generation**: Randomly generated food that increases the snake's length.
- **Scoring System**: Each player has their own score that increases when they eat food.
- **Collision Detection**: Snakes will reset if they collide with the canvas borders or themselves.

## Getting Started

To play the game, follow these steps:

cd two-player-snake-game
Controls
Player 1 Controls:

Move Up: W
Move Down: S
Move Left: A
Move Right: D
Player 2 Controls:

Move Up: Arrow Up
Move Down: Arrow Down
Move Left: Arrow Left
Move Right: Arrow Right
Files
index.html: The main HTML file that sets up the game canvas.
styles.css: Contains the styles for the game canvas and page.
script.js: The JavaScript file that contains the game logic.
How It Works
Game Initialization: The game initializes with two snakes and randomly placed food.
Movement: Players control their snakes using the specified keys. The snakes move in the direction of the pressed key.
Food Handling: When a snake eats the food, its length increases and the score for that player is updated.
Collision Handling: The game resets if a snake collides with the border or itself.
Contributing
Feel free to fork the repository and make improvements. Contributions to enhance the game or add new features are welcome!
