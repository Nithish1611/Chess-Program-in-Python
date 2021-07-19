# Chess-Program-in-Python
There are 11 functions of total
## chessmain
This function is the main function which calls all the functions. If we run this function we will get the game.
## chessboard
This function display the chess board with all the pieces. 
## checkpiece
This function check whether or not the player choose valid piece to move 
## opencheck
This function search is we move the selected piece whether our king is in direct threat of any opponent piece and if yes it return no possible move
## possiblemove
This function display the possible move once player choose the piece to move
## makemove
This function move the piece to the location the player choose if it is a valid location
## check 
This function check if opponent gives check to our king and if yes it allow only moves which get out of check
## blockcheck
This function check whether or not the location given by the player block the check if not it will not allow the piece to move there
## checkmate
If there is no move which block check this function display checkmate and the game over 
## draw 
This function check if we have any move to play after opponent play if not this display draw and the game over 
## kingmove 
This function help to find possible places for king to move it wont allow king to move in any opponent piece target location


