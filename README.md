Here's a README content for the given Tic Tac Toe Python script:

---

# Tic Tac Toe Game

## Description
This is a simple command-line based Tic Tac Toe game written in Python. The game allows two players (X and O) to take turns playing on a 3x3 grid, aiming to get three of their marks in a row either horizontally, vertically, or diagonally.

## Features
- **Two-player game**: Players alternate between "X" and "O".
- **Grid Display**: The current state of the game is displayed after each move.
- **Win Condition**: The game checks for a win after each move and announces the winner.
- **Interactive Gameplay**: Players are prompted to input their move, and the grid updates after each move.

## How It Works
1. The game starts by initializing two arrays, one for "X" (xState) and one for "O" (zState), both representing an empty 3x3 grid.
2. Players take turns entering a position (from 0 to 8) where they want to place their mark.
3. After each move, the board is displayed and the game checks if either player has won.
4. The game continues until one player wins or all the grid positions are filled.

## Installation

### Prerequisites
- Python 3.x

### Steps to Run the Game
1. Clone or download the repository.
2. Open a terminal or command prompt.
3. Navigate to the folder containing the Python file.
4. Run the script:
    ```bash
    python tic_tac_toe.py
    ```

## Game Rules
- **Player X** starts the game and chooses a spot on the grid by entering a number between 0 and 8.
- **Player O** follows the same rules, entering a number for their move.
- The game board will be displayed after every move with numbers (0-8) showing unoccupied spots and "X" or "O" marking the spots filled by each player.
- A player wins if they get three of their marks in a horizontal, vertical, or diagonal line.

## Code Overview
1. **sum(a, b, c)**: A helper function to check if three positions on the board are all marked by the same player.
2. **printBoard(xState, zState)**: Displays the current board with "X" and "O" in their respective spots or the numbers 0-8 if the spots are still available.
3. **checkWin(xState, zState)**: Checks for a winning condition. It checks all possible win combinations and announces the winner (X or O).
4. **Main Loop**: The game runs in a loop where players alternate turns. It checks the win conditions after every turn and ends when a player wins or all spots are filled.

## Example

```
Welcome to Tic Tac Toe
X's Chance
Please enter a value: 0
X | 1 | 2 
--|---|---
3 | 4 | 5 
--|---|---
6 | 7 | 8 
O's Chance
Please enter a value: 1
X | O | 2 
--|---|---
3 | 4 | 5 
--|---|---
6 | 7 | 8 
...
X Won the match
Match over
```

## Contributing
Feel free to contribute by:
- Reporting bugs or issues.
- Suggesting improvements or features.
- Submitting pull requests for fixes or features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this content based on additional details about your project!
