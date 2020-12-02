# Oska-Board-Game-AI
An artificial intelligence for the board game 'Oska,' to generate the next best possible move for a player to win given the number of moves to look ahead into the future. Implemented minimax search algorithm and created a unique static board evaluator to decide the next best move.

How to run on command line: 
Example: oskaplayer(['wwww','---','--','---','bbbb'],'w',2)
First argument is a string representation of the 2n-3 board. 
Second argument is either 'b' or 'w' to represent the player. 
Third argument is the number of moves to look ahead to.  
