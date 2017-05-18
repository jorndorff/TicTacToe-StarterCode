
Tic Tac Toe
===========

An interactive two-player tic-tac-toe game.


Usage
-----
Update this info

Example Execution
-------
Two players interact with the program as shown here.
```

Welcome to “Tic-Tac-Toe” game

Player 1, please enter your character: X 
Player 2, please enter your character: O


-------------
| 0 | 1 | 2 |
-------------
| 4 | 5 | 6 |
-------------
| 7 | 8 | 9 |
-------------
Player 1, please choose a cell: 4

-------------
| 0 | 1 | 2 |
-------------
| X | 5 | 6 |
-------------
| 7 | 8 | 9 |
-------------
Player 2, please choose a cell: 8 

-------------
| 0 | 1 | 2 |
-------------
| X | 5 | 6 |
-------------
| 7 | O | 9 |
-------------
```
The game continues taking input from the users until one player wins or the board is full.


Assignment Requirements
-----------------------

* You must use a two-dimensional list to represent your board

* You must break down your programs into meaningful functions

* You must use variables (and variable names) that are meaningful to your program

* You must document your project through comments and a README file, and follow other programming best-practices like writing clear commit messages, making incremental commits, and having `.gitignore` file

* You must handle invalid user input gracefully.

* You must choose one enhancement from the following list, or propose your own and get it pre-approved.



Enhancements
------------
* Allow a one-player game where a human plays against an AI.
* Allow the users to chose the size of the board.
* Allow more than two players to play.


Structure Suggestions
---------------------
You should have functions such as `init_board()` to initialize the board, `check_winner()` to check the winner or a tie, `place_symbol()` etc.You don't have to use these exact functions, but you do need to have logical separation of the different parts of your program.


Grading
--------
* Successfully implemented the two player game: 9 points
* Randomly chooses one player to go first: 1 points
* Proper git usage (.gitignore, reasonable commits and messages): 2 points
* Enhancement: 2 points
* Error handling: 1 point
* Effective function use and abstraction: 3 points
