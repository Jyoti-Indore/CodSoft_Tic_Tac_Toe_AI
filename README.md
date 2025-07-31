# 🎮 Unbeatable Tic-Tac-Toe AI using Minimax 🤖

This repository contains my **second task** as part of the **CodSoft Internship**. The project is a Python-based implementation of the classic **Tic-Tac-Toe** game, where a human plays against an **AI agent** built using the **Minimax algorithm with Alpha-Beta Pruning**.

---

## 📌 Project Objective

To develop an intelligent AI player for Tic-Tac-Toe that is **unbeatable**, demonstrating understanding of:
- Game theory concepts 🧠
- Adversarial search algorithms
- Python programming and logic structuring

---

## 💻 Tech Stack

- **Python 3**
- Standard libraries: `math`, `sys`

---

## ⚙️ Features

- Play as **X** against AI (**O**)
- AI uses **Minimax + Alpha-Beta Pruning** to make optimal moves
- Validates user inputs and prevents overwriting cells
- Simple command-line interface (no external dependencies)
- Guaranteed **win or draw** for the AI

---

## 🧠 How the AI Works

The AI simulates all possible game outcomes using the **Minimax algorithm**, assigning scores based on win/lose/draw states:

- Win: `+1`
- Lose: `-1`
- Draw: `0`

**Alpha-Beta Pruning** optimizes the Minimax tree by skipping unnecessary branches, making the algorithm faster without sacrificing correctness.

---

## 🕹️ How to Play

### ✅ Steps:

1. Run the game:python tictactoe.py

2. Enter positions (1–9) as shown:
   
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9


   git clone https://github.com/yourusername/tic-tac-toe-ai
   cd tic-tac-toe-ai
