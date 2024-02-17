# Simon-Says

Simon-Says is a Python-based implementation of the classic memory game. The game uses the Pygame library to create a graphical user interface where players can interact with the game.

## Game Description

In Simon-Says, players are presented with four colored buttons: green, red, blue, and yellow. The game will illuminate one of these buttons in a random sequence, and the player must repeat this sequence by clicking the buttons in the correct order. If the player succeeds, the sequence becomes progressively longer and faster. If the player makes a mistake, the game ends.

## Installation

To run Simon-Says, you need to have Python and Pygame installed on your machine. If you don't have Python installed, you can download it from the official website: https://www.python.org/downloads/

To install Pygame, you can use pip:

```bash
pip install pygame
```

## Running the Game

To start the game, navigate to the directory containing the game files and run the `main.py` script:

```bash
python main.py
```

## Game Files

The game consists of two main files:

- `main.py`: This is the main script that runs the game. It handles the game loop, user input, and game logic.

- `button.py`: This script defines the `Button` class, which is used to create the colored buttons in the game. Each button has properties such as its color, sound, and position on the screen.

## Sounds

The game uses four different sounds, one for each button. These sounds are stored as .mp3 files in the same directory as the game scripts. The sounds are played when the corresponding button is illuminated.
