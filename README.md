# Merge-sort
# Overview
This Python script implements the merge sort algorithm, a classic divide-and-conquer sorting algorithm that efficiently sorts arrays in O(n log n) time complexity.
How It Works
The merge sort algorithm follows these steps:

Divide: Split the array into two halves at the middle point
Conquer: Recursively sort both halves
Merge: Combine the sorted halves back into a single sorted array

# Algorithm Details

Time Complexity: O(n log n) in all cases (best, average, worst)
Space Complexity: O(n) for the temporary arrays
Stability: Yes - maintains relative order of equal elements
In-place: No - requires additional memory for temporary arrays

# Code Structure

merge_sort(array): Main recursive function that implements the merge sort algorithm
Base case: Arrays with length ≤ 1 are already sorted
Recursive case: Divides the array and recursively sorts both parts
Merging logic: Combines two sorted subarrays into one sorted array

# Features

Works with both integers and floating-point numbers
Sorts the array in-place (modifies the original array)
Includes demonstration code showing before and after sorting
