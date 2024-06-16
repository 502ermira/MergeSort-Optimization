# Analysis and Optimization of MergeSort

## Overview
This project involves the implementation and optimization of different variants of the MergeSort algorithm.

## Sorting Algorithms

### MergeSort
- **Description:** MergeSort is a divide-and-conquer sorting algorithm that recursively divides an array into smaller sub-arrays, sorts them, and merges the sorted sub-arrays to obtain the final sorted array.
- **Time Complexity:** O(n log n)
- **Space Complexity:** O(n)

### MergeSort 3-way
- **Description:** MergeSort 3-way is a variant that divides the array into three parts instead of two, potentially affecting performance and efficiency.
- **Time Complexity:** O(n log₃ n)
- **Space Complexity:** O(n)

### Bottom-up MergeSort
- **Description:** Bottom-up MergeSort iteratively sorts the array from the smallest sub-arrays up, improving space efficiency by eliminating recursion.
- **Time Complexity:** O(n log n)
- **Space Complexity:** O(n)

## Code Description
The provided code includes implementations for the following variants of MergeSort:

- **MergeSort:** Recursively divides the array into halves, sorts each half, and merges them.
- **MergeSort 3-way:** Divides the array into three parts, sorts each part, and merges them.
- **Bottom-up MergeSort:** Iteratively sorts and merges sub-arrays until the entire array is sorted.

Each algorithm efficiently handles arrays of various sizes while maintaining specified time and space complexities.

This README provides an overview of the project, emphasizing the implementation and optimization of MergeSort and its variants. The code is ready for use and further analysis.
