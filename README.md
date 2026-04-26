# 🎮 Unbeatable Tic-Tac-Toe AI
A tic-tac-toe AI program that never loses. This program uses the minimax algorithm with or without alpha-beta pruning to reduce the search space.

## 🤖 AI-Powered Game with Minimax (without Alpha-Beta Pruning)

### 🎓 Internship Project | Game AI & Search Algorithms

---

## ✨ **Features**

## 🚀 **How to Run**
```bash
1. Save as `tictactoe.html`
2. Double-click OR open in browser
3. Play as X (Blue) vs AI (Red O)
4. Watch AI make perfect moves!

## 🎮 **Game Rules**
- Player: X (Blue) - You go first
- AI: O (Red) - Perfect play guaranteed
- Win: 3 in a row/column/diagonal
- Draw: Board full, no winner

## ** Win Rate vs Human: 100% win/draw **
## Browser Support: Chrome, Firefox, Safari, Mobile


# Code Architecture
TicTacToe Class
├── board: string[9]     // Game state
├── scores: {player, ai, draws}
├── minimax(depth, alpha, beta)  // AI Brain
├── getBestMove()        // AI decision
├── checkWinner()        // 8 win patterns
└── updateDisplay()      // UI refresh 
