# Chess in Terminal ♟️

A fully playable **chess game in the terminal**, written **from scratch in Python**.

This project focuses on implementing core chess mechanics, move validation, and a clean terminal UI — without using external chess libraries.

⚠️ **Note:** This game requires a terminal that supports **ANSI color escape codes**.  
If your terminal does not support ANSI colors, the board and pieces will not display correctly.

---

## 🎮 Features

### ✅ Implemented
- Playable chess game in the terminal
- Colored board and pieces (ANSI escape codes)
- Full move validation for all pieces
- Check detection
- Pawn promotion
- Undoing moves
- Save & load game state

### ❌ Not Implemented (Yet)
- Checkmate
- Stalemate
- Castling
- En passant

---

## How to Play

1. Clone the repository:
   ```bash
   git clone https://github.com/Leshiro/chess-in-terminal.git
2. Navigate into the project folder:
   ```bash
   cd chess-in-terminal
3. Run the game:
   ```bash
   python chess.py

## Controls
Moves are entered as 4 characters. e.g: `e2e4`
- First two characters → piece position<br>
- Last two characters → destination

## Commands
- `save` — Save the current game
- `exit` / `quit` — Exit the game
- `restart` — Restart the game
- `undo` — Undo move

## Save System
- Saved games are stored in the `saves/` folder as `.txt` files.<br>
- You can load a save by entering its filename when starting the game.
