# How do sorting algorithm work?

## Insertion Sort [Best: O(N), Worst:O(N^2)]

Step 01. Takes the element and compares with the one before it.
Step 02. If the value of the element is lower, they swap places with the one on the left.
Step 03. It keeps trading places until reaching an element smaller than the current element.
Step 04. The algorithm repeats until reaching the last element on the right.

* It is very efficient for partially sorted, or tiny (less than 20 elements) arrays
+ The best case happens when the array is `already sorted` (Only the first loop is executed)
+ The worst case happens when the the array is `inverse sorted` (Both loops are executed)
