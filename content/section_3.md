# Section 3 - Sort Algorithms

## What are the main Sort algorithms?

- Bubble Sort
- Selection Sort
- Insertion Sort
- Shell Sort
- Merge Sort
- Quick Sort
- Counting Sort
- Stable Counting Sort
- Radix Sort

## What is Bubble Sort?

Bubble sort is a simple algorithm that repeatedly swaps adjacent elements, from left to right. 

- In-place algorithm
- Complexity - O (n^^2) (Quadratic)
- Stable algorithm

## What is Selection Sort?

Selection sort is an algorithm that finds the largest element and places it at the end.

The array is partitioned into two parts:

- Sorted sub-array
- Unsorted sub-array

Each iteration moves one item into the sorted sub-array.
 
- In-place algorithm
- Complexity - O (n^^2) (Quadratic)
- Unstable algorithm

## What is Insertion Sort?

Insertion sort is an algorithm that functions similarly to how you might sort a  pack of cards. Take a card, and place it in the sorted partition in the correct order.

- In-place algorithm
- Complexity - O (n^^2) (Quadratic)
- Stable algorithm

## What is Shell Sort?

Shell sort is a variation of insertion sort. The idea is to partially sort the array, then iteratively sort with a smaller gap. This reduces the total amount of shifting compared to Insertion sort.

The gap is calculated with various algorithms, but can be as simple as 

- 20
- 10
- 5
- 2
- 1

===

- In-place algorithm
- Complexity - Hard to calculate
- Unstable algorithm

## What is Merge Sort?

Merge sort is a 'Divide and Conquer' algorithm. First, the algorithm recursively divides the array into left and right arrays, until arrays contain 1 element.

Next, the algorithm merges back each array by ordering them. Each child array will be in the correct order.

- Not an in-place algorithm
- Complexity - O (n log n) (Loglinear)
- Stable algorithm

## What is Quick Sort?

Quick sort is a 'Divide and Conquer' algorithm. A first element is picked, either first or last. The other elements in the array are then sorted before or after the pivot element. 

After each pivot is implemented, each side can have its own pivot, and so on..

- In-place algorithm
- Complexity - O (n log n) (Loglinear)
- Unstable algorithm

## What is Counting Sort?

Counting sort is an algorithm that creates a temporary array, counting the number of occurrences of each number. Then, the array is repopulated in that order.

- Not in-place algorithm
- Complexity - O (n) (Linear)
- Unstable algorithm

## What is Stable Counting Sort?

Counting sort by default is not stable. To make it stable, the algorithm must:

- Calculate the cumulative number of occurrences of each digit/character
- Repopulate the array in reverse order

## What is Radix Sort?

Radix sort is an algorithm that sorts based on digits or characters. For example:

The items would be sorted by the last letter, then the next, etc.

`["jkdf", "jgio", "oiiu", "yhff", "adde"]`

The complexity depends on the algorithm used for the sorting of each character/digit.

## Stable vs Unstable Sort

When sorting an array with Duplicate numbers, will the ordering be preserved? (This could be important if you order by multiple attributes, such as name, then by age)

- Stable - maintain the correct ordering
- Unstable - doesn't maintain order

## What is Recursion?

Recursion is a method that calls itself, in order to loop through a task.