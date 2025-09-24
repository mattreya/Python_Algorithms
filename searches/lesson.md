
# Lesson: Searching Algorithms

Searching algorithms are designed to retrieve an element from any data structure where it is used. The efficiency of a search algorithm depends on the data structure in which the search is performed.

## 1. Basic Search Algorithms

These are the fundamental search algorithms. They are simple to understand but can be inefficient for large datasets.

*   **Linear Search:** The simplest search algorithm. It sequentially checks each element of the list until a match is found or the whole list has been searched.
    *   [Linear Search](linear_search.py)

## 2. Efficient Search Algorithms

These algorithms are more efficient and are used when the data is sorted.

*   **Binary Search:** A fast search algorithm with a time complexity of O(log n). It works on the principle of divide and conquer. For this algorithm to work properly, the data collection should be in a sorted form.
    *   [Binary Search](binary_search.py)
*   **Jump Search:** An improvement of linear search for sorted arrays. The basic idea is to check fewer elements (than linear search) by jumping ahead by fixed steps.
    *   [Jump Search](jump_search.py)
*   **Fibonacci Search:** A comparison-based technique that uses Fibonacci numbers to search an element in a sorted array.
    *   [Fibonacci Search](fibonacci_search.py)
*   **Exponential Search:** This algorithm is useful for unbounded searches, where the size of the array is infinite. It works by finding a range where the element is present and then using binary search in that range.
    *   [Exponential Search](exponential_search.py)
*   **Interpolation Search:** An improvement over Binary Search for instances, where the values in a sorted array are uniformly distributed.
    *   [Interpolation Search](interpolation_search.py)

## 3. Tree Traversal / Search

These algorithms are used to search for a node in a tree data structure.

*   **Binary Tree Traversal:** This includes Breadth-First Search (BFS) and Depth-First Search (DFS), which are fundamental graph traversal algorithms.
    *   [Binary Tree Traversal](binary_tree_traversal.py)

## 4. Heuristic Search Algorithms

These algorithms are used to find a "good enough" solution when an exact solution is hard to find. They are often used in Artificial Intelligence.

*   **Hill Climbing:** A mathematical optimization technique which is an iterative algorithm that starts with an arbitrary solution to a problem, then attempts to find a better solution by making an incremental change to the solution.
    *   [Hill Climbing](hill_climbing.py)
*   **Simulated Annealing:** A probabilistic technique for approximating the global optimum of a given function.
    *   [Simulated Annealing](simulated_annealing.py)
*   **Tabu Search:** A metaheuristic search method that uses local search methods to solve mathematical optimization.
    *   [Tabu Search](tabu_search.py)

Now that you've covered data structures, sorting, and searching, you have a strong foundation. A good next step would be to dive into **Graph Algorithms**.
