
# Lesson: Graph Algorithms

Graphs are a fundamental data structure in computer science, used to model relationships between objects. This lesson will guide you through the most important graph algorithms.

## 1. Graph Representations and Traversals

Before you can work with graphs, you need to know how to represent them and traverse them.

*   **Graph Representations:** Learn how to represent a graph in code. The two most common ways are adjacency lists and adjacency matrices.
    *   [Adjacency List](graph_adjacency_list.py)
    *   [Adjacency Matrix](graph_adjacency_matrix.py)
*   **Breadth-First Search (BFS):** A graph traversal algorithm that explores the neighbor nodes first, before moving to the next level neighbors.
    *   [Breadth-First Search](breadth_first_search.py)
*   **Depth-First Search (DFS):** A graph traversal algorithm that explores as far as possible along each branch before backtracking.
    *   [Depth-First Search](depth_first_search.py)

## 2. Shortest Path Algorithms

These algorithms are used to find the shortest path between two nodes in a graph.

*   **Dijkstra's Algorithm:** Finds the shortest path between a given node and all other nodes in a weighted graph. It only works for graphs with non-negative edge weights.
    *   [Dijkstra's Algorithm](dijkstra.py)
*   **Bellman-Ford Algorithm:** Finds the shortest path from a single source vertex to all of the other vertices in a weighted digraph. It is slower than Dijkstra's but can handle graphs with negative edge weights.
    *   [Bellman-Ford Algorithm](bellman_ford.py)
*   **A* Search Algorithm:** A popular pathfinding algorithm that is an extension of Dijkstra's. It is often used in games and web-based maps.
    *   [A* Search](a_star.py)
*   **Floyd-Warshall Algorithm:** An algorithm for finding the shortest paths in a weighted graph with positive or negative edge weights (but with no negative cycles).
    *   [Floyd-Warshall Algorithm](graphs_floyd_warshall.py)

## 3. Minimum Spanning Tree (MST) Algorithms

An MST is a subset of the edges of a connected, edge-weighted undirected graph that connects all the vertices together, without any cycles and with the minimum possible total edge weight.

*   **Kruskal's Algorithm:** A greedy algorithm that finds an MST by sorting all the edges from low weight to high and building the MST by adding edges that don't form a cycle.
    *   [Kruskal's Algorithm](minimum_spanning_tree_kruskal.py)
*   **Prim's Algorithm:** Another greedy algorithm that finds an MST by starting with one vertex and growing the MST by adding the cheapest edge that connects a vertex in the MST to a vertex outside the MST.
    *   [Prim's Algorithm](prim.py)

## 4. Other Important Graph Algorithms

*   **Topological Sort:** A linear ordering of the vertices of a directed acyclic graph (DAG).
    *   [Topological Sort](g_topological_sort.py)
*   **Strongly Connected Components (SCC):** A directed graph is called strongly connected if there is a path in each direction between each pair of vertices of the graph.
    *   [Kosaraju's Algorithm](scc_kosaraju.py)
    *   [Tarjan's Algorithm](tarjans_scc.py)
*   **Cycle Detection:** Algorithms to detect cycles in a graph.
    *   [Check Cycle](check_cycle.py)

With a solid understanding of graphs, you are now ready to tackle more advanced topics like **Dynamic Programming** and **Backtracking**.
