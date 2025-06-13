# AI Algorithms in Python

This repository contains Python implementations of classic artificial intelligence algorithms, demonstrated using Jupyter Notebooks.

## Notebooks Included

### 1.  8-Queens Problem Solver (`8-queens.ipynb`)

Solves the classic 8-Queens chess puzzle using a **backtracking** algorithm.

#### Problem Description

Place 8 queens on an 8×8 chessboard so that no two queens threaten each other — no same row, column, or diagonal.

#### How the Algorithm Works (Simple Explanation)

1. Start from the first row.
2. Try placing a queen in the first safe column.
3. Check:
   - No other queen should be in the same column or diagonal.
4. If safe, move to the next row.
5. If not safe, try next column.
6. If no columns work, backtrack to the previous row and move its queen.
7. Repeat until all 8 queens are safely placed.
8. Store or print the solution.

> This method uses **backtracking**, which explores possible placements and reverses when conflicts arise.

#### Algorithm Overview

- Recursive placement of queens row by row.
- Backtracking used to explore all valid positions.
- Prints all 92 unique solutions.

---

### 2.DFS, BFS, and UCS (`dfs-bfs-ucs.ipynb`)

Implements three major graph search algorithms:
- **DFS (Depth-First Search)**
- **BFS (Breadth-First Search)**
- **UCS (Uniform Cost Search)**

####  Use Case

Demonstrates how different graph traversal strategies behave in exploring nodes in a graph.

####  Algorithm Descriptions

- **DFS**: Explores as far as possible down one branch before backtracking.
- **BFS**: Explores all neighbors of a node before going deeper (guarantees shortest path in unweighted graphs).
- **UCS**: Expands the least-cost node first; optimal for weighted graphs with non-negative edge costs.



