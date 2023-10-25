# 2048-Game

## Description 
2048 is a simple grid-based numbers puzzle game. The player's objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048.

## Features
- Simple text-based interface for easy testing.
- Graphic user interface using the tkinter library for a more immersive experience.
- Game state logic to detect win, lose, and ongoing game statuses.
- Option to undo previous moves.

## How to Play
### Text-based Interface:
1. Run the text_play() function to start the game in text mode.
2. Use W (up), A (left), S (down), and D (right) keys to make your moves.
3. Press Q to quit the game anytime.

### Graphic User Interface:
1. Run the GameGrid(game_logic) class to start the game with the graphic interface.
2. Use the arrow keys or W, A, S, D keys to move the tiles.
3. Press Z to undo your last move.

### Installation & Setup
1. Ensure you have Python (version 3.x recommended) installed.
2. Clone this repository or download the source code.
3. Install required dependencies:
`pip install tkinter`

### Run the game!
`python 2048 Game.py`

## Game Logic
- The game starts with two tiles, both having the number '2'.
- Use the arrow keys to move the tiles. When two tiles with the same number touch, they merge into one!
- Every turn, a new tile will randomly appear in an empty spot on the board with a value of either 2 or 4.
- The game ends when the board is filled up and no adjacent tiles have the same value or when a tile reaches the value of 2048.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License 
[MIT License](https://github.com/AlagappanRa/2048-Game/blob/main/LICENSE) 
