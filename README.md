# 2 player Checkers (Human-VS-AI, Human-VS-Human)

## Features

- 🎮 Two-player mode (Human vs Human)
- 🤖 Single-player mode with AI opponent
- ⚙️ Adjustable AI difficulty levels (1-5)
- ♟️ Forced capture moves (following standard checkers rules)
- 👑 Automatic king promotion
- 🔄 Multiple jump captures in a single turn
- 🎨 Colorful console interface

## Requirements

- Python 3.x
- No external dependencies required

## Installation

1. Clone the repository:
git clone https://github.com/Rania-Ghazanfar/2-player-Checkers-Human-VS-AI-Human-VS-Human.git     

## How to Play

Choose to play against AI or another human. If playing against AI, select difficulty level (1-5).
Player 1 uses X pieces (moves downward)
Player 2/AI uses O pieces (moves upward)

## Game Rules

Regular pieces move diagonally forward.
Kings can move diagonally in any direction.
Captures are made by jumping over an opponent's piece.
Multiple jumps in a single turn are allowed.
Pieces are promoted to kings when reaching the opposite end of the board.
If a capture is available, it must be taken (forced capture rule).

## Controls

Enter piece coordinates in format LetterNumber (e.g., A3)
When multiple moves are available, select by number

## AI Implementation

Minimax algorithm with alpha-beta pruning.
Depth varies based on selected difficulty level.
Board evaluation considers: Piece counts and positions, King status, Center control, Potential opponent captures.

## Future Improvements
GUI implementation.
Online multiplayer.
Improved AI with machine learning.
Move history and undo functionality.
