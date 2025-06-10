# 8-Queens Problem Solver 🧠♟️


## 📌 Problem Description

The **8-Queens** puzzle is a classic chess problem that involves placing 8 queens on a standard 8×8 chessboard so that no two queens threaten each other. This means that no two queens can share the same row, column, or diagonal.

## 📂 Contents

- `8-queens.ipynb`: Jupyter Notebook implementing the 8-Queens solution algorithm.
- Visualization: Displays the board and queen placements for valid solutions.

## 🚀 Features

- Solves the 8-Queens problem using **backtracking**.
- Displays all possible solutions (92 in total).
- Visualizes each solution using a text-based board.
- Modular, well-commented Python code.

## 🧠 How the Algorithm Works (Simple Explanation)

1. Start with the first row of the chessboard.
2. Try placing a queen in the first column.
3. Check for safety:
   - No other queen should be in the same column or diagonal.
4. If it's safe:
   - Move to the next row and repeat the process.
5. If it's not safe:
   - Try the next column in the same row.
6. If no column works:
   - Backtrack to the previous row and move the queen to a new position.
7. Continue this process until all 8 queens are placed safely.
8. Save or print each valid solution.

