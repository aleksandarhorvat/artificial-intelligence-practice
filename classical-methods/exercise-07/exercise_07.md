Implement a program that creates a Minimax agent for the game Tic-Tac-Toe. An implementation of the game board is already provided (board.py), which defines the game rules and some useful methods. Additionally, create an agent that represents the user (a human player) and test the Minimax agent in a match against it.

The game should be played on a 3×3 board, and a win is achieved by connecting three identical symbols in a row (vertically, horizontally, or diagonally).

Since Tic-Tac-Toe is a relatively simple game, a basic Minimax algorithm can explore all possible states in a reasonably short time. However, to make it even more efficient, add alpha-beta pruning.

![tic_tac_toe](image.png)