# Analysis and Optimization of MergeSort

## Overview
This project involves the implementation and optimization of several sorting algorithms, focusing on different variants of the MergeSort algorithm. The provided code includes implementations for MergeSort, MergeSort 3-way, and Bottom-up MergeSort.

## Sorting Algorithms

### MergeSort
- **Description:** MergeSort is a divide-and-conquer sorting algorithm that recursively divides an array into smaller sub-arrays, sorts them, and merges the sorted sub-arrays to obtain the final sorted array.
- **Time Complexity:** O(n log n)
- **Space Complexity:** O(n)

### MergeSort 3-way
- **Description:** MergeSort 3-way is a variant of MergeSort that divides the array into three parts instead of two. This approach can affect performance and efficiency compared to traditional MergeSort.
- **Time Complexity:** O(n log₃ n)
- **Space Complexity:** O(n)

### Bottom-up MergeSort
- **Description:** Bottom-up MergeSort is an iterative version of MergeSort that sorts the array from the bottom (smallest sub-arrays) up, eliminating the need for recursion and potentially improving space efficiency.
- **Time Complexity:** O(n log n)
- **Space Complexity:** O(n)

## Code Description
The provided code includes implementations for the following sorting algorithms:

- **MergeSort:** Recursively divides the array into halves, sorts each half, and merges them.
- **MergeSort 3-way:** Divides the array into three parts, sorts each part, and merges them.
- **Bottom-up MergeSort:** Iteratively sorts and merges sub-arrays of increasing size until the entire array is sorted.

Each algorithm is designed to efficiently sort arrays of various sizes while maintaining the specified time and space complexities.

This README provides an overview of the project, highlighting the implementation and optimization of sorting algorithms, especially variants of MergeSort. The provided code is ready for use and further analysis.
