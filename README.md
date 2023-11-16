# Tic_Tac_Toe-with-AI

### Initialization:
The program initializes a GUI using the Tkinter library.
Creates a 3x3 grid of buttons to represent the Tic-Tac-Toe board.

### Game State Representation:
The game state is represented by a list self.board, which stores the current state of the Tic-Tac-Toe board.
The values in self.board can be "X", "O", or "" (empty).

### Player Turns:
The game starts with player "X".
Players take turns clicking on empty spots on the board to make their moves.

### Handling Button Clicks:
When a player clicks on a button, the on_button_click method is called.
Checks if the clicked spot is empty before making a move.
Updates the board state and disables the clicked button.
Checks for a winner or a draw after each move.

### Switching Players:
After each move, the current player is switched between "X" and "O".

### Resetting the Board:
The game can be reset by clicking the "Reset" button.
Resets the board state and enables all buttons.

### AI Opponent:
The AI opponent uses the minimax algorithm to make strategic moves.
The make_ai_move method is called after each player move to make the AI move.

### Minimax Algorithm:
The minimax algorithm is a recursive algorithm used to determine the best move for the AI.
It evaluates each possible move's score and selects the move with the highest or lowest score, depending on the player.
The algorithm considers all possible moves and their outcomes to make decisions.

### Winning Conditions:
The game checks for winning conditions after each move.
If a player has three in a row horizontally, vertically, or diagonally, the game declares that player as the winner.

### Announcing Results:
If there's a winner, the game displays a message box announcing the winner.
If the game is a draw, a message box announces the draw.

### GUI Updates:
The GUI is updated to reflect the current state of the game after each move.

### Event Handling:
The program uses event handling to respond to button clicks and update the game state accordingly.

### Main Loop:
The Tkinter main loop (root.mainloop()) keeps the GUI running and responsive to user actions.
