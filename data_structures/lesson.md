# Lesson: Introduction to Data Structures

Welcome to your first lesson! Data structures are a way of organizing and storing data so that they can be accessed and worked with efficiently. They are fundamental to computer science and are the building blocks of most algorithms.

We recommend you learn these data structures in the following order.

## 1. Linear Data Structures

These are the most basic data structures. They store data in a sequential manner.

*   **Linked Lists:** A linear collection of data elements, whose order is not given by their physical placement in memory. Instead, each element points to the next.
    *   [Singly Linked List](linked_list/singly_linked_list.py)
    *   [Doubly Linked List](linked_list/doubly_linked_list.py)
    *   [Circular Linked List](linked_list/circular_linked_list.py)
*   **Stacks:** A LIFO (Last-In, First-Out) data structure. Think of it like a stack of plates.
    *   [Stack](stacks/stack.py)
*   **Queues:** A FIFO (First-In, First-Out) data structure. Like a queue of people waiting for a bus.
    *   [Queue](queues/queue_by_list.py)
    *   [Priority Queue](queues/priority_queue_using_list.py)
    *   [Deque (Double-Ended Queue)](queues/double_ended_queue.py)

## 2. Non-Linear Data Structures

These data structures don't store data in a sequential way.

*   **Trees:** A hierarchical data structure with a root value and subtrees of children with a parent node.
    *   [Binary Search Tree](binary_tree/binary_search_tree.py)
    *   [AVL Tree](binary_tree/avl_tree.py)
    *   [Red-Black Tree](binary_tree/red_black_tree.py)
*   **Heaps:** A specialized tree-based data structure that satisfies the heap property.
    *   [Heap](heap/heap.py)
*   **Graphs:** A set of nodes (or vertices) and a set of edges that connect pairs of nodes.
    *   [Graph (Adjacency List/Matrix)](../graphs/)
*   **Hash Tables:** A data structure that implements an associative array abstract data type, a structure that can map keys to values. In Python, dictionaries are a built-in implementation of hash tables.
    * [Hashing](hashing/hashing.py)

## 3. Advanced Data Structures

Once you have a good grasp of the basics, you can move on to these more advanced data structures.

*   **Tries:** A tree-like data structure that proves to be very efficient for solving problems related to strings.
    *   [Trie](trie/trie.py)
*   **Fenwick Trees (Binary Indexed Trees):** A data structure that can efficiently update elements and calculate prefix sums in a table of numbers.
    *   [Fenwick Tree](binary_tree/fenwick_tree.py)
*   **Segment Trees:** A tree data structure for storing information about intervals, or segments.
    *   [Segment Tree](binary_tree/segment_tree.py)
*   **Disjoint Set Union (DSU):** A data structure that keeps track of a set of elements partitioned into a number of disjoint (non-overlapping) subsets.
    *   [Disjoint Set Union](disjoint_set/disjoint_set.py)

Once you feel comfortable with these data structures, you can move on to the next lesson: **Sorting and Searching**.