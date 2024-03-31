# Snake Game README

## Overview
This is a simple implementation of the classic Snake game in C++ using the cpp4 library. The player controls a snake that moves around the screen, eating food to grow longer. The game ends if the snake collides with itself or the boundaries of the screen.

## Features
- Simple and intuitive controls using arrow keys.
- Food randomly generated on the screen for the snake to eat.
- Score tracking to keep track of the player's progress.
- Game over screen displaying the final score and offering the option to play again.

## Requirements
- C++ compiler that supports C++11 or later.
- cpp4 library (included in this repository).

## Installation
1. Clone this repository to your local machine.
2. Compile the source code using your C++ compiler. For example:
    ```
    g++ -std=c++11 main.cpp -o snake_game
    ```
3. Run the compiled executable.

## How to Play
- Use the arrow keys (up, down, left, right) to control the snake's direction.
- Eat food (denoted by *) to grow longer and increase your score.
- Avoid colliding with the snake's own body or the boundaries of the screen.
- The game ends when the snake collides, and your final score is displayed.

## Controls
- Up Arrow: Move the snake up.
- Down Arrow: Move the snake down.
- Left Arrow: Move the snake left.
- Right Arrow: Move the snake right.
- q: Quit the game.

## Acknowledgements
This game is implemented using the cpp4 library, which provides simple graphics and input handling functionalities.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
