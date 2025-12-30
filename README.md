# ♟️ Chess Alpha

![Python](https://img.shields.io/badge/python-3.13-blue) ![Pygame](https://img.shields.io/badge/pygame-2.6.1-blue)

A complete & customizable **chess engine**, written from scratch in Python; including legal move validation, game-state management, save & load functionality, and a clean Pygame GUI with interactive controls. 

This project focuses on designing & implementing a complete chess engine - without using external chess libraries.

## ✔️ Features
### ⚙️ Engine
- Legal move validation for all pieces
- Check, checkmate, stalemate
- Pawn promotion
- Castling
- En passant
- Undoing moves
- Saving & loading games

### 🎮 Game UI
- Clean Pygame UI with interactive buttons
- Changing board palette

## 🛠️ Built With
- `Python 3.13`
- `Pygame 2.6.1`

## How to Run
1. Click **Code → Download ZIP** on this repository.
2. Extract the ZIP file to a folder.
3. Open the folder and run `game.py`.

## How to Run (Alternative)
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
├── game.pyw       # Launcher
└── gui.py         # Pygame UI
```
