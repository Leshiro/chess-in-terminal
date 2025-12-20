# Chess in Terminal ♟️

A fully playable **chess game in the terminal**, written **from scratch in Python**.

This project focuses on implementing core chess mechanics, move validation, and a clean terminal UI — without using external chess libraries.

---

## 🎮 Features

### ✅ Implemented
- Playable chess game in the terminal
- Full move validation for all pieces
- Pawn promotion
- Capture detection
- Colored board and pieces (ANSI escape codes)
- Save & load game state

### ❌ Not Implemented (Yet)
- Check detection
- Checkmate
- Stalemate
- Castling
- En passant

---

## 🖥️ How to Play

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chess-in-terminal.git
Navigate into the project folder:

bash
Copy code
cd chess-in-terminal
Run the game:

bash
Copy code
python chess.py
🧠 Controls
Moves are entered as 4 characters:

nginx
Copy code
e2e4
First two characters → piece position

Last two characters → destination

Commands
save — Save the current game
exit / quit — Exit the game
restart — Restart from the beginning

💾 Save System
Saved games are stored in the saves/ folder

You can load a save by entering its filename when starting the game

🛠️ Built With Python 3
No external libraries
ANSI escape codes for color rendering

📁 Project Structure
powershell
Copy code
chess-in-terminal/
│
├── chess.py
├── saves/
│   └── *.txt
├── .gitignore
└── README.md

📜 License
This project is open-source and available under the MIT License.
