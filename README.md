# README: Tic Tac Toe

This is a simple implementation of the classic game Tic Tac Toe using Python and the `Tkinter` UI package. 

## Requirements

- Python 3.x
- `Tkinter` UI package (usually included with Python installation)

## How to Run

1. Clone this repository to your local machine or download the `tictactoe.py` file.
2. Open a terminal and navigate to the directory where the `tictactoe.py` file is located.
3. Run the command `python tictactoe.py` or `python3 tictactoe.py` (depending on your Python installation).

## How to Play

1. The game is played on a 3x3 grid.
2. Player 1 uses "X" and Player 2 uses "O".
3. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game.
4. If all spaces on the board are filled and no player has won, the game ends in a tie.

## Game Interface

![Tic Tac Toe UI](/images/tictactoe.png)

## Implementation Details

The `tictactoe.py` file contains a `Tkinter` GUI interface with 9 buttons representing the game board. The state of each button is tracked using a global variable. When a button is clicked, the corresponding state is updated to "X" or "O" depending on whose turn it is. 

After each move, the program checks if either player has won the game. If a player has won, a message box is displayed declaring the winner and all buttons are disabled. If the game ends in a tie, a message box is displayed indicating the tie and all buttons are disabled. 

The program also contains a `disable_all_buttons()` function that disables all buttons on the game board, and a `checkifwon()` function that checks if either player has won the game.