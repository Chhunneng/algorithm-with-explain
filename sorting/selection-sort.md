# Selection Sort

Selection Sort is an algorithm that sorts an array by repeatedly finding the minimum element from the unsorted part of the array and putting it at the beginning.

## Algorithm

1. Find the minimum element in the unsorted part of the array.
2. Swap the minimum element with the first element of the unsorted part of the array.
3. Increase the index of the first element of the unsorted part of the array.
4. Repeat steps 1-3 until the entire array is sorted.

## Example

Let's consider the following array of integers: [64, 25, 12, 22, 11]

### First pass

The minimum element in the unsorted part of the array is `11`. We swap it with the first element of the unsorted part of the array (`64`), resulting in the following array: [11, 25, 12, 22, 64]

### Second pass

The minimum element in the unsorted part of the array is `12`. We swap it with the first element of the unsorted part of the array (`25`), resulting in the following array: [11, 12, 25, 22, 64]

### Third pass

The minimum element in the unsorted part of the array is `22`. We swap it with the first element of the unsorted part of the array (`25`), resulting in the following array: [11, 12, 22, 25, 64]

### Fourth pass

The minimum element in the unsorted part of the array is `25`. We swap it with the first element of the unsorted part of the array (`25`), resulting in the following array: [11, 12, 22, 25, 64]

The entire array is now sorted.

## Time complexity

The time complexity of Selection Sort is O(n^2), where n is the number of elements in the array.

## Space complexity

The space complexity of Selection Sort is O(1), since only a constant amount of additional space is needed to store the minimum element and swap the elements.
