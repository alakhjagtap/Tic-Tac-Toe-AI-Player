# Tic Tac Toe Game

This is a simple implementation of the Tic Tac Toe game in Python. The game can be played between a human player and an AI player. The AI player uses the minimax algorithm to determine the best move.

## Getting Started

To get started with the game, clone this repository to your local machine.

git clone https://github.com/your_username/tic-tac-toe.git

### Prerequisites

This game requires Python 3.x to be installed on your system.

### Usage

Navigate to the project directory and run the tictactoe.py file to start the game.

cd tic-tac-toe
python tictactoe.py

Follow the prompts to input your moves. You will be asked to input a number between 0 and 8 to select the position on the board.

## Gameplay

The game is played on a 3x3 grid. Players take turns placing their marks ('X' or 'O') on the board. The first player to align three of their marks horizontally, vertically, or diagonally wins the game. If all the squares are filled and no player has won, the game ends in a tie.

### Board Representation

The board is represented as follows:

| 0 | 1 | 2 |
| 3 | 4 | 5 |
| 6 | 7 | 8 |

### Example Gameplay

|   |   |   |
|   |   |   |
|   |   |   |

X's turn. Input move (0-8): 4
X makes a move to square 4
|   |   |   |
|   | X |   |
|   |   |   |

O's turn. Input move (0-8): 0

O makes a move to square 0
| O |   |   |
|   | X |   |
|   |   |   |
...

## Players

### Human Player

A human player can input their moves through the terminal.

### AI Player

The AI player uses the minimax algorithm to determine its moves.

### Random Player

A player that makes random moves.

