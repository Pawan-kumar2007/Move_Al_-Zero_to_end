# Move_Al_-Zero_to_end
Move All Zeroes to End
**Problem**

Given an array, move all 0s to the end of the array while maintaining the relative order of the non-zero elements.

**Example**

Input:

[1, 0, 3, 0, 5]

Output:

[1, 3, 5, 0, 0]
**Approach**
Create an ArrayList to store all non-zero elements.
Traverse the array and add every non-zero element to the list.
Copy the elements from the ArrayList back into the original array.
Fill the remaining positions of the array with 0.
