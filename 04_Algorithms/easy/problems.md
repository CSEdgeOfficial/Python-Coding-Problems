# Algorithms - Easy Problems

## Problem 1: Linear Search
**Type:** Implementation  
**Estimated Time:** 10 minutes  
**Concept Focus:** Linear search algorithm

### Description
Implement linear search to find the index of a target element in a list.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100)
- Second line: n space-separated integers (the array)
- Third line: An integer target (element to search)

### Output Specification
- Print the index (0-based) of the target element
- Print "-1" if element not found

### Test Cases

**Test Case 1:**
```
Input:
5
10 20 30 40 50
30
Output: 2
```

**Test Case 2:**
```
Input:
4
5 10 15 20
100
Output: -1
```

---

## Problem 2: Bubble Sort
**Type:** Implementation  
**Estimated Time:** 15 minutes  
**Concept Focus:** Bubble sort algorithm

### Description
Implement bubble sort to sort a list of integers in ascending order.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100)
- Second line: n space-separated integers

### Output Specification
- Print the sorted array elements separated by spaces

### Test Cases

**Test Case 1:**
```
Input:
5
64 34 25 12 22
Output: 12 22 25 34 64
```

**Test Case 2:**
```
Input:
4
5 1 4 2
Output: 1 2 4 5
```

---

## Problem 3: Binary Search
**Type:** Implementation  
**Estimated Time:** 15 minutes  
**Concept Focus:** Binary search on sorted array

### Description
Implement binary search to find a target element in a sorted array.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100)
- Second line: n space-separated integers in ascending order
- Third line: An integer target

### Output Specification
- Print the index (0-based) of target
- Print "-1" if not found

### Test Cases

**Test Case 1:**
```
Input:
7
1 3 5 7 9 11 13
7
Output: 3
```

**Test Case 2:**
```
Input:
5
2 4 6 8 10
5
Output: -1
```

---

## Problem 4: Find Minimum
**Type:** Implementation  
**Estimated Time:** 10 minutes  
**Concept Focus:** Finding minimum with single pass

### Description
Find the minimum element in an unsorted array using a single pass.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100)
- Second line: n space-separated integers

### Output Specification
- Print the minimum element

### Test Cases

**Test Case 1:**
```
Input:
6
45 23 67 12 89 34
Output: 12
```

**Test Case 2:**
```
Input:
4
-5 -10 -3 -8
Output: -10
```

---

## Problem 5: Two Sum
**Type:** Implementation  
**Estimated Time:** 15 minutes  
**Concept Focus:** Array traversal and searching

### Description
Find two numbers in an array that add up to a specific target. Return their indices.

### Input Specification
- First line: An integer n (2 ≤ n ≤ 100)
- Second line: n space-separated integers
- Third line: An integer target (sum to find)

### Output Specification
- Print two indices (0-based) separated by space
- If multiple pairs exist, print the first pair found
- Print "-1 -1" if no pair exists

### Test Cases

**Test Case 1:**
```
Input:
4
2 7 11 15
9
Output: 0 1
```

**Test Case 2:**
```
Input:
3
3 2 4
6
Output: 1 2
```
