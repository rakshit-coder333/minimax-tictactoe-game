# minimax-tictactoe-game
An unbeatable AI opponent using the recursive Minimax algorithm.

## 🚀 Features
*   **Optimal Play:** The AI uses a recursive Minimax algorithm to play perfectly.
*   **Win/Loss Tracker:** Keeps track of scores across multiple rounds.
*   **Dynamic UI:** A clean Command Line Interface (CLI) that clears the screen for a smooth gaming experience.

  ## 🧠 How the Minimax Algorithm Works

The AI views the game as a tree of possibilities. For every move, it recursively explores all potential future moves until it reaches a terminal state (Win, Loss, or Draw).

### The Scoring System
The algorithm assigns a heuristic value to each terminal state:
*   **AI Wins:** +10 points
*   **Human Wins:** -10 points
*   **Draw:** 0 points

  ## 🛠️ Tech Stack Used
*   **Language:** Python 3.x
*   **Algorithm:** Minimax (Recursive Depth-First Search)
*   **Environment:** Terminal / Google Colab
