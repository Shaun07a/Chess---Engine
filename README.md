# Chess Engine 

A complete Chess Engine built using **Python** and **Pygame**, featuring a graphical chessboard, legal move generation, advanced chess rules, and an AI opponent powered by the **Negamax algorithm with Alpha-Beta Pruning**. The project demonstrates object-oriented programming, game state management, recursive search algorithms, and multithreading to provide a smooth gameplay experience.

---

## Features

- Interactive chessboard built with Pygame
- Human vs Human mode
- Human vs AI mode
- AI vs AI mode
- Legal move generation for all pieces
- Move validation
- Smooth move animations
- Move log panel displaying the entire game history
- Undo moves (`Z`)
- Reset game (`R`)
- Background AI computation using multithreading
- Responsive GUI while the AI is thinking

---

## Chess Rules Implemented

- Standard piece movement
- Captures
- Pawn Promotion
- En Passant
- Kingside Castling
- Queenside Castling
- Check Detection
- Checkmate Detection
- Stalemate Detection
- Pins
- Double Check Handling
- Discovered Checks

---

## AI Features

The chess engine includes multiple search algorithms:

- Random Move Selection
- Minimax
- Negamax
- Negamax with Alpha-Beta Pruning

### Board Evaluation

The AI evaluates positions using:

- Material count
- Piece-square tables (Positional Evaluation)
- Checkmate detection
- Stalemate detection

This allows the engine to make stronger positional decisions instead of relying solely on material advantage.

---

## Technologies Used

- Python 3
- Pygame
- Object-Oriented Programming
- Multithreading

---

## Project Structure

```text
Chess/
│
├── ChessMain.py          # Main game loop and GUI
├── ChessEngine.py        # Chess logic and move generation
├── SmartMoveFinder.py    # AI algorithms
├── images/               # Chess piece images
└── README.md
```

---

## Controls

| Key | Action |
|------|--------|
| Left Mouse Click | Select and move a piece |
| Z | Undo previous move |
| R | Reset the game |

---

## Installation

### Clone the repository

```bash
git clone https://github.com/Shaun07a/Chess---Engine.git
```

### Navigate into the project

```bash
cd Chess---Engine
```

### Install dependencies

```bash
pip install pygame
```

### Run the application

```bash
python ChessMain.py
```

---

## Search Algorithm

The AI searches for the best move using:

```text
Negamax
      │
      ▼
Alpha-Beta Pruning
      │
      ▼
Position Evaluation
      │
      ▼
Best Move
```

Alpha-Beta pruning significantly reduces the number of evaluated positions, resulting in faster AI move generation without affecting playing strength.

---

## Recent Improvements

- Added Negamax search algorithm.
- Added Alpha-Beta pruning for faster move searching.
- Added positional evaluation using piece-square tables.
- Implemented move animations.
- Added a move log panel displaying moves in chess notation.
- Implemented multithreading so the AI calculates moves in the background without freezing the GUI.
- Improved overall engine performance and move ordering.
- Fixed bugs related to castling, en passant, move generation, board synchronization, and AI decision-making.

---

## Future Improvements

- Opening Book
- Iterative Deepening
- Quiescence Search
- Transposition Tables (Zobrist Hashing)
- Better Move Ordering (MVV-LVA, Killer Moves, History Heuristic)
- Adjustable AI Difficulty
- Time Controls
- PGN Import/Export
- FEN Support
- Threefold Repetition Detection
- Fifty-Move Rule
- Draw by Insufficient Material

---

## Screenshots

Add screenshots of the application here.

---

## Learning Outcomes

This project strengthened my understanding of:

- Object-Oriented Programming
- Chess Engine Architecture
- Recursive Algorithms
- Minimax
- Negamax
- Alpha-Beta Pruning
- Multithreading in Python
- Game State Management
- GUI Development using Pygame
- Performance Optimization

---

## Acknowledgements

This project was built as a practical exploration of chess programming, artificial intelligence, and search algorithms. It provided valuable experience in designing a complete game engine while implementing advanced chess mechanics and AI techniques from scratch.

---

