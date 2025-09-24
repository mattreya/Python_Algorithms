
# Lesson: Dynamic Programming

Dynamic Programming (DP) is a powerful technique for solving optimization problems by breaking them down into simpler subproblems. It is often used for problems where you are looking for the maximum or minimum value of something, or the number of ways to do something.

DP is all about storing the results of subproblems to avoid re-computation. This is called memoization.

## 1. Introductory Problems

These problems are a great way to get started with DP.

*   **Fibonacci Sequence:** The classic example to illustrate the power of memoization.
    *   [Fibonacci](fibonacci.py)
*   **Climbing Stairs:** A simple problem that can be solved using the same logic as the Fibonacci sequence.
    *   [Climbing Stairs](climbing_stairs.py)

## 2. Classic DP Problems

These are the problems you will almost certainly encounter in a technical interview.

*   **Knapsack Problem:** Given a set of items, each with a weight and a value, determine the number of each item to include in a collection so that the total weight is less than or equal to a given limit and the total value is as large as possible.
    *   [Knapsack](knapsack.py)
*   **Longest Common Subsequence:** Find the longest subsequence common to all sequences in a set of sequences.
    *   [Longest Common Subsequence](longest_common_subsequence.py)
*   **Longest Increasing Subsequence:** Find the length of the longest subsequence of a given sequence such that all elements of the subsequence are sorted in increasing order.
    *   [Longest Increasing Subsequence](longest_increasing_subsequence.py)
*   **Edit Distance:** Find the minimum number of edits (insertions, deletions, or substitutions) needed to transform one string into another.
    *   [Edit Distance](edit_distance.py)
*   **Matrix Chain Multiplication:** Find the most efficient way to multiply a given sequence of matrices.
    *   [Matrix Chain Multiplication](matrix_chain_multiplication.py)

## 3. Variations and Other Problems

*   **Coin Change:** Find the minimum number of coins required to make a given amount.
    *   [Minimum Coin Change](minimum_coin_change.py)
*   **Subset Sum:** Determine if there is a subset of a given set of integers that sums to a given value.
    *   [Sum of Subset](sum_of_subset.py)
*   **Word Break:** Determine if a given string can be segmented into a space-separated sequence of one or more dictionary words.
    *   [Word Break](word_break.py)

Dynamic Programming can be tricky, so don't be discouraged if you don't get it right away. The key is to practice identifying the subproblems and the recursive relationship between them.

After this, you can explore **Backtracking**, which is another powerful algorithmic technique.
