# Insertion-Sort
Insertion Sort is a simple sorting algorithm that works by repeatedly inserting an element from the unsorted portion of the array into its correct position in the sorted portion of the array. It works similarly to how we sort a deck of cards in our hands.

To implement insertion sort, we start by iterating over the array starting from the second element. We save the current element as key and compare it with the elements in the sorted portion of the array from right to left. For each element that is greater than key, we shift it one position to the right to make room for key. When we find an element that is less than or equal to key, we insert key into the position immediately to its right.

We repeat this process for each element in the unsorted portion of the array until the entire array is sorted. At each iteration, the sorted portion of the array grows by one element.

The time complexity of insertion sort is O(n^2) in the worst case, where n is the number of elements in the array. However, it has a best case time complexity of O(n) when the array is already sorted or nearly sorted, making it an efficient algorithm for small or partially sorted arrays.
