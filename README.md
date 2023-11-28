# TictacToe
# Tic-Tac-Toe Game

## Overview
This is a simple console-based Tic-Tac-Toe game implemented in C++. The game allows a player to compete against a computer opponent.

## How to Play
1. The game board is a 3x3 grid.
2. Players take turns to place their symbol ('X' for human, 'O' for computer) in an empty cell.
3. The first player to have three of their symbols in a row (horizontally, vertically, or diagonally) wins.
4. The game ends in a draw if the board is filled without a winner.

## Instructions
- Compile the code using a C++ compiler (e.g., g++).
- Run the compiled executable.
- Follow the on-screen instructions to make your moves.

## Code Structure
- `main()`: Entry point of the program.
- `playTicTacToe(int whoseTurn)`: Main game loop where players take turns.
- `showBoard(char board[][SIDE])`: Display the current state of the game board.
- `showInstructions()`: Display the game instructions.
- `initialise(char board[][SIDE], int moves[])`: Initialize the game board and moves.
- `declareWinner(int whoseTurn)`: Declare the winner of the game.
- `rowCrossed(char board[][SIDE])`, `columnCrossed(char board[][SIDE])`, `diagonalCrossed(char board[][SIDE])`: Check if any row, column, or diagonal is crossed by the same player's move.
- `gameOver(char board[][SIDE])`: Check if the game is over.

## Additional Notes
- The computer's moves are randomly generated.
- The game uses a simple console interface.

## Author
- Mamnun Mumin Eram
- Roll: 222-115-254
