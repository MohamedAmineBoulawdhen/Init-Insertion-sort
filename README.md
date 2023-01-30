# Insertion Sort Algorithm

Insertion sort is a simple sorting algorithm that works by sorting elements in a list one at a time, similar to the way we sort playing cards in our hands. 
It is an in-place sorting algorithm, meaning it sorts the list in place without creating a copy of the list.

## How it Works

The algorithm begins by assuming that the first element in the list is already sorted. 
Then, for each subsequent element in the list, the algorithm inserts the element into its proper position in the sorted portion of the list. 
This is done by shifting elements to the right until the proper position is found. The process continues until the entire list is sorted.

## Instructions
- Each time work only with the first i-1 element from of the array.
- Pick element arr[i] and insert it into sorted sequence in the array from 0 to i-1.

## Time Complexity

The time complexity of the insertion sort algorithm is `O(n^2)`, where `n` is the number of elements in the list. 
This makes the insertion sort algorithm inefficient for large lists, as the time it takes to sort the list grows quadratically with the size of the list. 
However, the algorithm is efficient for small lists and has the advantage of being easy to understand and implement.

## Conclusion

Insertion sort is a simple and straightforward sorting algorithm that is easy to understand and implement. 
It is not efficient for large lists, but it is a good algorithm to understand and use as a building block for more advanced sorting algorithms.
---
Don't forget to star this repository ⭐️ after you've finished the project. Your support is greatly appreciated!


