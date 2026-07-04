# Python Chess Engine

A fully functional chess game developed using **Python** and **Pygame**, featuring complete chess rules, animated gameplay, and an AI opponent using the **Minimax algorithm with Alpha-Beta Pruning**.

---

## Features

- Complete chess gameplay
- Legal move generation
- Check detection
- Checkmate detection
- Stalemate detection
- Castling (Kingside & Queenside)
- En Passant
- Pawn Promotion
- Undo move functionality
- Move animations
- Highlight selected pieces and valid moves
- AI opponent
- Random AI
- Minimax AI
- NegaMax Search
- Alpha-Beta Pruning
- Game restart
- Human vs Human
- Human vs AI
- AI vs AI

---

## Technologies Used

- Python 3
- Pygame

---

## Project Structure

```
Chess/
│
├── ChessMain.py          # Main game loop and UI
├── ChessEngine.py        # Game state and move generation
├── SmartMoveFinder.py    # AI algorithms
│
├── images/
│   ├── wp.png
│   ├── bp.png
│   ├── wK.png
│   ├── bK.png
│   └── ...
│
└── README.md
```

---

## AI Implementations

The project includes multiple AI strategies:

### Random Move AI
- Chooses a random legal move.

### Material-Based AI
- Evaluates moves based on material advantage.

### Minimax Algorithm
- Searches future positions to determine the strongest move.

### NegaMax
- Simplified implementation of Minimax.

### Alpha-Beta Pruning
- Optimizes Minimax by pruning unnecessary branches, significantly improving search speed.

---

## Chess Rules Implemented

- Standard piece movement
- Pawn double move
- Pawn promotion
- En Passant
- Kingside castling
- Queenside castling
- Check
- Checkmate
- Stalemate

---

## Controls

| Key | Action |
|------|--------|
| Mouse | Select and move pieces |
| Z | Undo last move |
| R | Restart the game |

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/python-chess-engine.git
```

Navigate to the project folder

```bash
cd python-chess-engine
```

Install dependencies

```bash
pip install pygame
```

Run the game

```bash
python ChessMain.py
```

---

## Screenshots

You can add screenshots of the game here.

Example:

```
screenshots/
├── gameplay.png
├── checkmate.png
└── ai-vs-player.png
```

---

## Future Improvements

- Opening Book
- Piece-Square Tables
- Better Evaluation Function
- Iterative Deepening
- Transposition Tables (Zobrist Hashing)
- Move Ordering Heuristics
- Quiescence Search
- Multiplayer Support
- PGN Export/Import
- FEN Support
- Chess Clock
- Adjustable AI Difficulty

---

## Learning Outcomes

This project demonstrates concepts including:

- Object-Oriented Programming
- Recursion
- Game Tree Search
- Minimax Algorithm
- NegaMax Algorithm
- Alpha-Beta Pruning
- Move Generation
- State Management
- Pygame Graphics
- Event Handling
- Animation

