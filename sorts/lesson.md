
# Lesson: Sorting Algorithms

Sorting algorithms are used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.

It's important to understand the trade-offs between these algorithms in terms of time and space complexity.

## 1. Simple Sorts (Good for Beginners)

These are the first sorting algorithms you should learn. They are simple to understand and implement, but not very efficient for large datasets.

*   **Bubble Sort:** Repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order.
    *   [Bubble Sort](bubble_sort.py)
*   **Selection Sort:** Repeatedly finds the minimum element from the unsorted part and puts it at the beginning.
    *   [Selection Sort](selection_sort.py)
*   **Insertion Sort:** Builds the final sorted array one item at a time.
    *   [Insertion Sort](insertion_sort.py)

## 2. Efficient Sorts

These algorithms are more efficient and widely used in practice.

*   **Merge Sort:** A divide-and-conquer algorithm that divides the array into two halves, sorts them, and then merges them.
    *   [Merge Sort](merge_sort.py)
*   **Quick Sort:** Another divide-and-conquer algorithm that picks an element as a pivot and partitions the given array around the picked pivot.
    *   [Quick Sort](quick_sort.py)
*   **Heap Sort:** A comparison-based sorting technique based on a Binary Heap data structure.
    *   [Heap Sort](heap_sort.py)

## 3. Specialized Sorts

These algorithms are designed for specific types of data and can be very efficient in those cases.

*   **Counting Sort:** An integer sorting algorithm that operates by counting the number of objects that have each distinct key value.
    *   [Counting Sort](counting_sort.py)
*   **Radix Sort:** A non-comparative integer sorting algorithm that sorts data with integer keys by grouping keys by the individual digits which share the same significant position and value.
    *   [Radix Sort](radix_sort.py)
*   **Topological Sort:** A linear ordering of the vertices of a directed acyclic graph (DAG).
    *   [Topological Sort](topological_sort.py)

## 4. "Joke" or Inefficient Sorts

These are interesting to know about from a theoretical perspective, but you would never use them in a real-world application.

*   **Bogo Sort:** Also known as "permutation sort" or "stupid sort", it works by generating permutations of the list until it finds one that is sorted.
    *   [Bogo Sort](bogo_sort.py)
*   **Stalin Sort:** A "sorting" algorithm that iterates through the list and removes any elements that are not in order.
    *   [Stalin Sort](stalin_sort.py)

After mastering sorting, a good next step is to learn about **Searching Algorithms**.
