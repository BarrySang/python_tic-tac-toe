# Python Tic-Tac-Toe

A simple, terminal-based Tic-Tac-Toe game built with Python. It supports two-player local play, win detection, tie detection, and a quick restart/quit flow.

## Features

- Two-player gameplay on the same keyboard
- Board rendering in the terminal
- Automatic winner detection for rows, columns, and diagonals
- Tie detection when the board is full
- Restart or quit after each round
- No external dependencies required

## Requirements

- Python 3.8 or newer

## Getting Started

1. Clone or download the project.
2. Open a terminal in the project folder.
3. Run:

```bash
python main.py
```

## How to Play

- The board is numbered from 1 to 9.
- Players take turns entering a number corresponding to an empty square.
- Example board layout:

```text
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9
```

- Enter `q` at any move prompt to quit the game.
- After a round ends, press `r` to play again or `q` to exit.

## Example Gameplay

```text
Player X's turn
Enter a number (1-9) or 'q' to quit: 5
Player O's turn
Enter a number (1-9) or 'q' to quit: 1
...
```

## Project Structure

```text
python_tic_tac_toe/
├── main.py          # Game logic and user interaction
├── README.md        # Project documentation
```

## Notes

This project is intentionally lightweight and easy to understand, making it a good starting point for learning Python basics such as loops, conditionals, functions, and user input handling.

## License

This project is provided as-is for educational and personal use.
