# Sorting Algorithms

This repository contains C functions that implement various sorting algorithms for sorting arrays of integers and doubly linked lists in ascending order. The sorting algorithms included in this repository are Bubble sort, Insertion sort, Selection sort, and Quick sort. Each sorting function is designed to print the array or list after each swap operation for better visualization.

## Bubble Sort

The `bubble_sort` function sorts an array of integers in ascending order using the Bubble sort algorithm. It has the following prototype:

```c
void bubble_sort(int *array, size_t size);
```

### Big O Notations (Bubble Sort)

In the best case: O(n)
In the average case: O(n^2)
In the worst case: O(n^2)

## Insertion Sort

The `insertion_sort_list` function sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm. It is designed to swap the nodes themselves, not the integer values within the nodes. The prototype is as follows:

```c
void insertion_sort_list(listint_t **list);
```

### Big O Notations (Insertion Sort)

In the best case: O(n)
In the average case: O(n^2)
In the worst case: O(n^2)

## Selection Sort

The `selection_sort` function sorts an array of integers in ascending order using the Selection sort algorithm. The prototype is as follows:

```c
void selection_sort(int *array, size_t size);
```

### Big O Notations (Selection Sort)

In the best case: O(n^2)
In the average case: O(n^2)
In the worst case: O(n^2)

## Quick Sort

The `quick_sort` function sorts an array of integers in ascending order using the Quick sort algorithm with the Lomuto partition scheme. The pivot is always the last element of the partition being sorted. The prototype is as follows:

```c
void quick_sort(int *array, size_t size);
```

### Big O Notations (Quick Sort)

In the best case: O(n log n)
In the average case: O(n log n)
In the worst case: O(n^2)

This README provides an overview of the sorting algorithms implemented in this repository. Feel free to explore the code and use these sorting functions in your projects.
