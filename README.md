# tic-tac-toe
This code is a Python implementation of the classic Tic Tac Toe game using the tkinter library for GUI.
#The code defines a class TicTacToe that contains all the logic for the game. The __init__ method of the 
class sets up the GUI with 9 buttons arranged in a 3x3 grid, which represent the spaces on the Tic Tac Toe board.The buttons are stored in a list called buttons so that they can be easily accessed later.
The click method is called whenever a button is clicked and updates the text on the button to either
 "X" or "O" to represent the move made by the player. The check_winner() method is called after each move
 to see if either player has won the game. The method checks for three in a row horizontally, 
vertically, and diagonally. 
#The empty_spaces method updates the title of the game window to show who has won or either it is a tie.
The new_game method is called to start a new game.
A reset_button variable is declared and a restart button is set in the game window.The restart button is used to restart the game.  
The mainloop method is called at the end to start the GUI event loop and display the game window.

