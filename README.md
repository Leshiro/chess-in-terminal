# Chess Alpha ♟️

A fully functional **chess engine** written from scratch in Python.

This project focuses on implementing core chess mechanics, move validation, and a clean Pygame UI — without using external chess libraries.

## 🛠️ Built With
- `Python 3.13`
- `Pygame 2.6.1`

## 🎮 Features

### ✅ Implemented
- Fully functional Pygame UI
- Full move validation for all pieces
- Check, checkmate, stalemate
- Castling
- Pawn promotion
- Undoing moves
- Saving & loading games

### ❌ Not Implemented Yet
- En passant

## How to Play
1. Download code as ZIP
2. Extract code from ZIP
3. Run `game.py`
OR
1. Clone the repository: `git clone https://github.com/Leshiro/chess-alpha.git`
2. Navigate into the project folder: `cd chess-alpha`
3. Run the game: `python game.py`

## 📁 Project Structure
``` bash
chess-alpha/
├── assets/        # Images & audio
├── permanent/     # Permanent game data
├── saves/         # Saved games
├── colors.py      # Colors & palettes
├── config.py      # UI settings
├── engine.py      # Chess engine
├── game.py        # Start file
└── gui.py         # Pygame UI
