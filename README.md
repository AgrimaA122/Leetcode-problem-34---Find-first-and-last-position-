# Leetcode-problem-34---Find-first-and-last-position-
Solution for problem 34 on leetcode 

### Description

In this experiment, the **Find First and Last Position of Element in Sorted Array** problem was solved using a **linear search** approach. The array was traversed from the beginning to find the first occurrence of the target and from the end to find the last occurrence.

### Steps Taken

1. Take the sorted array and target value as input.
2. Initialize `startingPosition` and `endingPosition` as `-1`.
3. Traverse the array from left to right.
4. When the target is found, store its index as the starting position.
5. Traverse the array from right to left.
6. When the target is found, store its index as the ending position.
7. Return both positions as `{startingPosition, endingPosition}`.
8. If the target is not present, return `{-1, -1}`.

### Time Complexity

**O(n)** — The array is traversed twice in the worst case.

### Space Complexity

**O(1)** — Only a few variables are used apart from the output vector.
