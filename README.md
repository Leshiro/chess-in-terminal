# Chess Alpha ♟️

A fully playable **chess engine**, written **from scratch in Python**.

This project focuses on implementing core chess mechanics, move validation, and a clean Pygame UI — without using external chess libraries.

## 🎮 Features

### ✅ Implemented
- Playable chess game in the terminal
- Colored board and pieces (ANSI escape codes)
- Full move validation for all pieces
- Check, checkmate, stalemate
- Castling
- Pawn promotion
- Undoing moves
- Save & load game state

### ❌ Not Implemented (Yet)
- En passant

---

## How to Play

1. Clone the repository:
   ```bash
   git clone https://github.com/Leshiro/chess-alpha.git
2. Navigate into the project folder:
   ```bash
   cd chess-alpha
3. Run the game:
   ```bash
   python run.py
- `restart` — Restart the game
- `undo` — Undo move

## Save System
- Saved games are stored in the `saves/` folder as `.txt` files.<br>
- You can load a save by entering its filename when starting the game.
