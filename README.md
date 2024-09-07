# Tic_Tac_Toe

**This code implements a simple Tic Tac Toe game for two players, X and O. The game is played on a 3x3 grid, with players taking turns to enter their moves**.


Key Features:

Game Board: The game board is represented by two lists, xState and zState, which keep track of the positions occupied by X and O, respectively.

Move Input: Players enter their moves by inputting a number between 0 and 8, which corresponds to a position on the game board.

Input Validation: The code checks for invalid inputs, such as numbers outside the range 0-8, and prompts the player to enter a valid move.

Position Occupancy Check: The code checks if a position is already occupied by the other player and prompts the player to choose another position.

Win Condition Check: After each move, the code checks if the current player has won the game by examining all possible winning combinations.

Draw Condition Check: If all positions are occupied and no player has won, the code declares a draw.

Game Loop: The game continues until a player wins or a draw is declared.


**Functions**:

printBoard(xState, zState): Prints the current state of the game board.

checkWin(xState, zState): Checks if the current player has won the game or if it's a draw.

main(): The main game loop that handles player input, updates the game board, and checks for win or draw conditions.

Overall, this code provides a simple and functional implementation of a Tic Tac Toe game, with input validation and win/draw condition checks to ensure a smooth gaming experience.




