# Selection Sort in C

This repository contains an implementation of the Selection Sort algorithm in C. Selection Sort is a simple comparison-based sorting algorithm that sorts an array by repeatedly finding the minimum element from the unsorted part and putting it at the beginning. It is not suitable for large data sets as its average and worst-case complexity are both O(n^2), where n is the number of items being sorted.

## Overview of Functions

1. `void selection_sort(int arr[], int n)`: This function takes an integer array `arr` of size `n` as input and sorts it using the Selection Sort algorithm.

2. `void print_array(int arr[], int size)`: This function takes an integer array `arr` and its size as input, and prints the elements of the array.

## Sample Usage and Output

Here is an example of how to use the Selection Sort implementation with an integer array:

```c
int main() {
    int arr[] = {64, 25, 12, 22, 11};
    int n = sizeof(arr) / sizeof(arr[0]);

    printf("Original array:\n");
    print_array(arr, n);

    selection_sort(arr, n);

    printf("Sorted array:\n");
    print_array(arr, n);

    return 0;
}
```

## Outputs

```c
Original array:
64 25 12 22 11
Sorted array:
11 12 22 25 64
```
