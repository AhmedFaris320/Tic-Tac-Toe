# Tic-Tac-Toe
# 🎮 Tic Tac Toe — AI + Undo/Redo + PvP

> A Python-based interactive **Tic Tac Toe** game built using **Pygame** that brings **Data Structures & Algorithms** to life!  
> Features an intelligent AI (Minimax + Alpha-Beta Pruning), a stack-based Undo/Redo system, and both **Player vs Player** and **Player vs AI** modes — all with a clean, modern interface.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Pygame-2.x-green?style=for-the-badge&logo=pygame" />
  <img src="https://img.shields.io/badge/AI-Minimax%20%2B%20AlphaBeta-orange?style=for-the-badge" />
</p>

---

## 🧠 Data Structures & Algorithms (DSA) Used

| Concept | Usage in Project | Description |
|----------|------------------|--------------|
| **2D Lists (Matrices)** | Game Board (`board[3][3]`) | Stores cell states as X, O, or blank. |
| **Stack (LIFO)** | Undo/Redo System | Implemented via `move_stack` and `redo_stack`. |
| **Minimax Algorithm** | AI Decision Logic | Explores all possible game states to pick the best move. |
| **Alpha-Beta Pruning** | Minimax Optimization | Prunes branches that don’t affect the final decision. |
| **Recursion** | AI Search | Minimax recursively explores future moves. |
| **Game Tree** | Logical Representation | Each node represents a possible board state. |
| **Backtracking** | Undoing simulated moves | Helps AI evaluate all outcomes efficiently. |

---

## ⚙️ Features

✅ **Two Game Modes**
- 👥 *Play vs Player (Local PvP)* – alternate turns between two human players.  
- 🤖 *Play vs AI* – compete against a Minimax-powered computer.

✅ **Undo/Redo System**
- Implemented using **Stacks (LIFO)**.  
- Undo last move or redo previously undone moves.

✅ **Smart AI**
- Uses **Minimax Algorithm + Alpha-Beta Pruning** for perfect play.  
- Always finds the best move possible.

✅ **Interactive Menu**
- Choose between “Play vs AI” and “Play vs Player” on the start screen.

✅ **Polished UI**
- Smooth colors, button hover effects, and round transitions using Pygame.

✅ **Automatic Game Reset**
- Detects Win, Draw, and resets after a short delay.

---

## 🧩 File Structure

TicTacToe_AI_Undo/
│
├── main.py # 🎮 Main game file (all logic, UI, and event handling)
├── README.md # 📝 Project documentation (you're reading it)
├── requirements.txt # ⚙️ Dependencies (e.g., Pygame)
│
└── assets/ # 🎨 (Optional) For future icons, sounds, or images
├── icon.png # 🧩 Game icon (optional)
└── bg_music.mp3 # 🎵 Background music (optional)
