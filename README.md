# Tic-Tac-Toe

A two-player command-line tic-tac-toe game written in Python.

Players take turns placing **X** and **O** on a 3×3 board. The first player to get three marks in a row, column, or diagonal wins. If the board fills up with no winner, the game is a draw.

## Requirements

- Python 3

## How to run

From this folder:

```bash
python tictactoe.py
```

On some systems you may need `python3` instead of `python`.

## How to play

1. Player **X** goes first, then players alternate.
2. On each turn, enter a row and a column as two numbers from **1 to 3**, separated by a space.

   Example: `2 3` places a mark in row 2, column 3.

3. Occupied cells cannot be reused. Invalid input is rejected and you are asked to try again.
4. The game ends when a player wins or the board is full (draw).

## Project structure

- `tictactoe.py` — game loop, board display, win/draw checks, and input handling
