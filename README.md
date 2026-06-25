# Tic-Tac-Toe (C++)

A console-based two-player Tic-Tac-Toe game built in C++, using a 3x3 grid with full win and draw detection.

## Features
- Two-player turn-based gameplay (Player 1 = X, Player 2 = O)
- Win detection across all rows, columns, and both diagonals
- Draw detection when the board is full with no winner
- Input validation — rejects out-of-range moves and already-occupied cells
- Simple 1-3 row/column input (no zero-indexing confusion for the player)

## How to run
g++ main.cpp -o main
./main

## What I learned
- Working with 2D arrays to represent a grid
- Writing functions that return true/false (boolean logic) to check game state
- Nested loops for iterating through rows and columns
- Input validation and handling edge cases
