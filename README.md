# ActionScript ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common ActionScript error: the `ArrayIndexOutOfBoundsException`.  This exception occurs when you attempt to access an array element using an index that is out of range (less than 0 or greater than or equal to the array's length).  The example shows how this can happen and provides a solution. 

## Bug
The `bug.as` file contains code that attempts to access the element at index `myArray.length` of an array.  Since arrays are zero-indexed, this always attempts to access an element beyond the array's last valid element (resulting in the exception). 

## Solution
The `bugSolution.as` file presents a corrected version. The solution uses a conditional statement to ensure index is within valid range before accessing the array element.