# Flappy Bird Clone

This is a simple Flappy Bird clone built using the Phaser 3 game framework. The game challenges players to navigate a bird through obstacles without hitting the ground or columns.

## Features

- **Physics-based gameplay**: The bird is affected by gravity and can be controlled using the keyboard.
- **Dynamic obstacles**: Columns are placed at different heights to challenge the player.
- **Win and lose conditions**: Players win by reaching the end of the screen and lose by colliding with obstacles or the ground.
- **Instructions and feedback**: The game provides instructions and updates the player with messages based on their progress.

## Project Structure

├── app.js # Main game logic
├── index.html # HTML file to load the game
└── assets/ # Game assets (images)
├── background.png
├── bird.png
├── column.png
└── road.png

## How to Play

1. Open `index.html` in a web browser.
2. Press the **space bar** to start the game.
3. Use the **up arrow key** to make the bird fly upward.
4. Avoid hitting the columns or the ground.
5. Reach the right edge of the screen to win the game.

## How to Run the Project

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. Ensure you have an internet connection to load the Phaser 3 library from the CDN.

## Dependencies

- [Phaser 3](https://phaser.io/) (loaded via CDN)

## Game Assets

The following assets are used in the game and are located in the `assets/` directory:

- `background.png`: The background image of the game.
- `bird.png`: The sprite sheet for the bird character.
- `column.png`: The obstacle columns.
- `road.png`: The ground texture.

## License

This project is for educational purposes and does not include any specific license. Please ensure you have the rights to use the assets if you modify or distribute the project.
