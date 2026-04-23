# Tic Tac Toe (C++ CLI Game)

A fully functional command-line Tic Tac Toe game built in C++, designed with clean modular structure, robust input handling, and complete game state management.

This project focuses on building a reliable interactive system rather than just implementing basic game logic.

---

## Features

### Core Gameplay
- Two-player mode (Player X vs Player O)
- Turn-based gameplay with automatic player switching
- Real-time win detection (rows, columns, diagonals)
- Draw detection when the board is full

### Robust Input System
- Prevents invalid inputs (non-numeric, out-of-range)
- Prevents overwriting already occupied cells
- Continuously prompts until valid input is provided

### Game Session Control
- Replay system to play multiple rounds without restarting program
- Score tracking across games:
  - Tracks wins for Player X and Player O
  - Displays score after each game

### Clean Code Structure
- Modular function-based design
- Separation of concerns:
  - Input handling
  - Validation
  - Game logic
  - Display
- Central game loop controlling the entire flow

---

## Technical Concepts Used

- 2D arrays for board representation
- Functions and modular programming
- Loops for control flow and validation
- Conditional logic for game decisions
- Input stream handling (`cin`, fail-state recovery)
- Basic state management

---

## How the Game Works

1. Board is initialized with positions (1–9)
2. Players take turns entering positions
3. Each move is validated before being applied
4. After every move:
   - Check for win
   - Check for draw
5. Game ends when:
   - A player wins
   - OR the board is full (draw)
6. User can choose to play again

---

## How to Run

### Compile:
```bash
g++ main.cpp -o game
