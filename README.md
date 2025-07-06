# ♟ Chess Engine with AI (Python + Pygame)

This is a **fully playable chess engine with AI opponent**, built in Python using the `pygame` library. It supports all major chess rules including **castling**, **en passant**, **pawn promotion**, **checkmate**, and **stalemate**. The AI uses **Negamax with Alpha-Beta pruning** for efficient move search.

## 🧠 Features

* ✔️ Player vs Player (hotseat)
* 🤖 Player vs AI (minimax + alpha-beta)
* ⟲ Undo Moves
* ♚ Castling (both sides)
* ♟ En Passant capture
* ♛ Automatic pawn promotion to Queen
* 🔄 Restart game
* 📦 Clean object-oriented structure with `ChessEngine.py` and `SmartMoveFinder.py`

## 🗆 Project Structure

```
Chess-Engine/
├── ChessMain.py           # Pygame GUI and main game loop
├── ChessEngine.py         # Game state and move rules
├── SmartMoveFinder.py     # AI using Negamax + Alpha-Beta
├── images/                # Piece images (png format)
│   ├── wp.png, bK.png ... # White/Black pieces
├── README.md
└── requirements.txt       # (Optional) pip dependencies
```

## 🎡 Controls

| Action            | Key / Mouse      |
| ----------------- | ---------------- |
| Select/Move Piece | Left Mouse Click |
| Undo Move         | `Z` key          |
| Restart Game      | `R` key          |
| Quit Game         | Close window     |

## 🧠 AI Logic

The AI uses:

* **Negamax Search**
* **Alpha-Beta Pruning**
* **Basic material evaluation**
* Configurable search depth (`DEPTH` in `SmartMoveFinder.py`)

Evaluation is based on standard material values:

* Queen = 10
* Rook = 5
* Bishop/Knight = 3
* Pawn = 1

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/AmbarSinha24/Chess-Engine.git
cd Chess-Engine
```

### 2. Set up a Virtual Environment (recommended)

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install pygame
```

### 4. Run the Game

```bash
python ChessMain.py
```

## 🧑‍💻 Author

**Ambar Sinha**
GitHub: [@AmbarSinha24](https://github.com/AmbarSinha24)

