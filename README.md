# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The bug occurs when attempting to access an array element outside its bounds.  The solution provides a corrected version with a proper loop condition.

## Bug Description:

The provided Java code iterates through an integer array using a loop that goes one step beyond the valid index. This results in an `ArrayIndexOutOfBoundsException` when the code tries to assign a value to arr[5], which is outside the array bounds (0-4).

## Solution:

The solution fixes the loop condition so that the loop terminates before attempting to access an invalid index.