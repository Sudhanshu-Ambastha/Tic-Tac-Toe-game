# TikTakToe
This is a simple console-based TikTakToe game implemented in C. The player competes against the computer in a 3x3 grid.

## File
TikTakToe.c: The source code for the game.

## How to Play
1. Start the Game: Run the program. You will be prompted to enter your moves.
  
2. Player Move: Enter the row and column numbers (1-3) to place your 'X' on the board.
  
3. Computer Move: The computer will place an 'O' on the board in a random empty position.
  
4. Winning Condition: The first player to align three of their symbols (either 'X' or 'O') horizontally, vertically, or diagonally wins the game.

5. Tie Condition: If all spaces are filled and no player has won, the game ends in a tie.
  
## Functions
- resetBoard(): Initializes or resets the game board.
  
- printBoard(): Displays the current state of the game board.
  
- checkFreeSpaces(): Counts and returns the number of free spaces left on the board.

- playerMove(): Prompts the player to enter their move.
  
- computerMove(): Randomly places a computer move on the board.

- checkWinner(): Checks the board to determine if there's a winner.
printWinner(char winner): Displays the result of the game based on the winner.

## Compilation and Execution
To compile the game, use the following command:
```
gcc -o TikTakToe TikTakToe.c
```

To run the compiled program:
```
./TikTakToe
```
## Dependencies
Standard C library