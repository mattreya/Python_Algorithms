
# Lesson: Backtracking

Backtracking is a general algorithmic technique that considers searching every possible combination in order to solve a computational problem. It is a refined brute force approach that incrementally builds candidates to the solutions, and abandons a candidate ("backtracks") as soon as it determines that the candidate cannot possibly be completed to a valid solution.

## 1. Introductory Problems

These problems are a great way to get started with backtracking.

*   **All Permutations:** Generate all possible permutations of a given set of distinct numbers.
    *   [All Permutations](all_permutations.py)
*   **All Combinations:** Generate all possible combinations of a given set of distinct numbers.
    *   [All Combinations](all_combinations.py)

## 2. Classic Backtracking Problems

These are the problems you will likely encounter in a technical interview.

*   **N-Queens Problem:** The N-Queens puzzle is the problem of placing N chess queens on an N×N chessboard so that no two queens threaten each other.
    *   [N-Queens](n_queens.py)
*   **Sudoku Solver:** Write a program to solve a Sudoku puzzle by filling the empty cells.
    *   [Sudoku](sudoku.py)
*   **Rat in a Maze:** A maze is given as N*N binary matrix of blocks where source block is the upper left most block i.e., maze[0][0] and destination block is lower rightmost block i.e., maze[N-1][N-1]. A rat starts from source and has to reach destination.
    *   [Rat in a Maze](rat_in_maze.py)
*   **Word Search:** Given a 2D board and a word, find if the word exists in the grid.
    *   [Word Search](word_search.py)

## 3. Other Backtracking Problems

*   **Combination Sum:** Find all unique combinations in a candidate set of numbers (without duplicates) where the candidate numbers sum to a target.
    *   [Combination Sum](combination_sum.py)
*   **Generate Parentheses:** Given n pairs of parentheses, write a function to generate all combinations of well-formed parentheses.
    *   [Generate Parentheses](generate_parentheses.py)
*   **Hamiltonian Cycle:** A Hamiltonian cycle is a cycle in a graph that visits each vertex exactly once.
    *   [Hamiltonian Cycle](hamiltonian_cycle.py)

Backtracking is a powerful tool for solving a wide range of problems. The key is to understand how to build the solution incrementally and how to prune the search space.

This concludes the core algorithmic topics. You can now explore other areas of the repository, such as **Bit Manipulation**, **Ciphers**, or **Machine Learning**, depending on your interests.
