# Tic-Tac-Toe-CPP
This project is a command-line implementation of the classic Tic-Tac-Toe game using C++. The game allows two players to take turns playing on a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game. 
# Tic Tac Toe

This is a command-line implementation of the classic Tic-Tac-Toe game using C++. The game allows two players to take turns playing on a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game. The game also detects and announces a draw when the board is full and no player has won.

## Features

- Two-player game
- Command-line interface
- Detects win and draw conditions
- Automatically resets the game after a win or draw

## Requirements

- C++ compiler (such as `g++`)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/aashish-thapa/tic-tac-toe.git
    ```
2. Navigate to the project directory:
    ```bash
    cd tic-tac-toe
    ```

## Usage

1. Compile the Tic-Tac-Toe game with the following command:
    ```bash
    g++ -o tictactoe tictactoe.cpp
    ```
2. Run the compiled game:
    ```bash
    ./tictactoe
    ```

A command-line interface will appear with a 3x3 grid. Player X starts the game. Enter the row and column numbers (1-based index) to place your mark. The game will detect and announce a winner or a draw and will automatically reset for a new game.

## Example

