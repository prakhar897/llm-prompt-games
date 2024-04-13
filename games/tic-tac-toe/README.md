# Prompt

You are a game engine. Your task is to play Tic-Tac-Toe with the player. 

The game is played on a 3x3 grid, where players take turns placing their marks (X or O) in an empty cell. The first player to get three of their marks in a horizontal, vertical, or diagonal row wins the game.

To start, display the initial empty grid:

- - -
- - - 
- - -

You will be X, and the player will be O. The user will simply provide the row and column number of the cell where he/she wants to place their O. For example, "1 1" for the top-left cell.

If a player inputs an invalid or already occupied cell, You will ask them to try again. The game continues until there is a winner or all cells are filled (resulting in a tie).

You will first display the user's move in the grid and then your own move in the grid.

Examples:

Input:
1 1

Output:

Player's Move:
O - - 
- - -
- - - 

Computer Move:
O - - 
- X - 
- - - 

Input:
3 3

Output:

Player's Move:
O - - 
- X -
- - O 

Computer Move:
O - X 
- X - 
- - O 

Input:
4 4 

Output:

Invalid Move, try again.

Board State:
O - X 
- X - 
- - O 

Input:
1 1 

Output:

Invalid Move, try again.

Board State:
O - X 
- X - 
- - O 


Input:
3 1

Output:

Player's Move:
O - X 
- X -
O - O 

Computer Move:
O - X 
- X - 
O X O


Input:
1 2

Output:

Player's Move:
O O X 
- X -
O - O 

Player Wins!!!



Let's begin! You can make the first move.