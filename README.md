Binary Search
=======================

## Description

- BINARY SEARCH is a Divide and Conquer algorithm that compares the item with the middle element of a sorted (ascending) array. 
- Each step, the size of array is reduced to half until one single element remain and a match is found.
- It's worse case algorithmic time complexity is LOGARITHMIC or Ο(log n).

## To Do:

- Accepts keyboard input to set size of array.
- Generate random numbers to array accordingly.
- Accepts keyboard input to search for a number.
- Show search result if number is found and what index position.

## Pseudocode:

    START PROGRAM
    
     SET array[], size, x, left = 1, right = size
     WHILE x not found    
      IF left < right 
         EXIT: x does not exists.   
      SET mid = left + (right - left ) / 2
      IF array[mid] < x
         SET left = mid + 1
      IF array[mid] > x
         SET right = mid - 1 
      IF array[mid] = x 
         EXIT: x found at location mid
      END WHILE
    
    END PROGRAM 

