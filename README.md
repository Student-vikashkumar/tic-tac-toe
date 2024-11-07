# Tic-Tok-Toe
Explanation
Board Setup: The board array represents the Tic Tac Toe grid. Initially, each slot is filled with numbers from 1 to 9.
drawBoard(): This function prints the current state of the board.
placeMarker(): This function places the player's marker (X or O) on the board if the chosen slot is available.
checkWin(): This function checks rows, columns, and diagonals to see if there is a winning combination.
swapPlayerAndMarker(): This function switches between Player 1 and Player 2 and changes the marker accordingly.
game(): The main game function, handling player input, turns, and checking win or draw conditions.
How to Play
Players take turns selecting a slot (1-9).
The board updates with each player's choice.
The game announces a winner if a player gets three in a row, or a draw if all slots are filled without a winner.
