# Bubble Sort

Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted. The algorithm, which is a comparison sort, is named for the way smaller or larger elements "bubble" to the top of the list.

## Algorithm

The algorithm can be described as follows:

1. Loop through the array
2. Compare each element to its neighbor
3. If the neighbor is greater than the element, swap them
4. Repeat steps 1-3 for each element in the array
5. Continue repeating steps 1-4 until no swaps are made

## Example

Let's take an example of an unsorted array `[5, 3, 8, 6, 7, 2]` and see how Bubble Sort works:

1. First pass:
   - (5, 3) - Swap - [3, 5, 8, 6, 7, 2]
   - (5, 8) - No Swap - [3, 5, 8, 6, 7, 2]
   - (8, 6) - Swap - [3, 5, 6, 8, 7, 2]
   - (8, 7) - Swap - [3, 5, 6, 7, 8, 2]
   - (8, 2) - Swap - [3, 5, 6, 7, 2, 8]

2. Second pass:
   - (3, 5) - No Swap - [3, 5, 6, 7, 2, 8]
   - (5, 6) - No Swap - [3, 5, 6, 7, 2, 8]
   - (6, 7) - No Swap - [3, 5, 6, 7, 2, 8]
   - (7, 2) - Swap - [3, 5, 6, 2, 7, 8]

3. Third pass:
   - (3, 5) - No Swap - [3, 5, 6, 2, 7, 8]
   - (5, 6) - No Swap - [3, 5, 6, 2, 7, 8]
   - (6, 2) - Swap - [3, 5, 2, 6, 7, 8]

4. Fourth pass:
   - (3, 5) - No Swap - [3, 5, 2, 6, 7, 8]
   - (5, 2) - Swap - [3, 2, 5, 6, 7, 8]

5. Fifth pass:
   - (3, 2) - Swap - [2, 3, 5, 6, 7, 8]

The sorted array is `[2, 3, 5, 6, 7, 8]`.

## Time complexity

The worst-case time complexity of the bubble sort algorithm is O(n^2). The best-case time complexity is O(n) when the input array is already sorted.

## Space complexity

The space complexity of the bubble sort algorithm is O(1) since it uses a constant amount of extra space to store temporary variables.

## Applications

Bubble sort is not commonly used in practice due to its poor performance compared to other sorting algorithms like quicksort and mergesort. However, it is a simple algorithm that is easy to understand and implement, and can be useful for educational purposes.

## References

- [Bubble sort - Wikipedia](https://en.wikipedia.org/wiki/Bubble_sort)
