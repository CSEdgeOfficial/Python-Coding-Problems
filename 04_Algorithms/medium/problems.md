# Algorithms - Medium Problems

## Problem 1: Merge Sort
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Divide and conquer, merge sort algorithm

### Description
Implement merge sort to sort an array of integers in ascending order.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 1000)
- Second line: n space-separated integers

### Output Specification
- Print the sorted array elements separated by spaces

### Test Cases

**Test Case 1:**
```
Input:
6
38 27 43 3 9 82
Output: 3 9 27 38 43 82
```

**Test Case 2:**
```
Input:
5
5 2 8 1 9
Output: 1 2 5 8 9
```

---

## Problem 2: Quick Sort
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Divide and conquer, partitioning

### Description
Implement quick sort to sort an array of integers using the last element as pivot.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 1000)
- Second line: n space-separated integers

### Output Specification
- Print the sorted array elements separated by spaces

### Test Cases

**Test Case 1:**
```
Input:
5
10 7 8 9 1
Output: 1 7 8 9 10
```

**Test Case 2:**
```
Input:
6
64 34 25 12 22 11
Output: 11 12 22 25 34 64
```

---

## Problem 3: Breadth-First Search (BFS)
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Graph traversal using queue

### Description
Implement BFS traversal on an undirected graph starting from a given node.

### Input Specification
- First line: Two integers n and e (1 ≤ n ≤ 100, 0 ≤ e ≤ 1000) - nodes and edges
- Next e lines: Two integers u and v representing an edge
- Last line: Starting node for BFS

### Output Specification
- Print the BFS traversal order (space-separated node numbers)
- Nodes are numbered from 0 to n-1
- When multiple nodes can be visited, choose the smaller numbered node first

### Test Cases

**Test Case 1:**
```
Input:
5 6
0 1
0 2
1 3
1 4
2 4
3 4
0
Output: 0 1 2 3 4
```

**Test Case 2:**
```
Input:
4 3
0 1
1 2
2 3
0
Output: 0 1 2 3
```

---

## Problem 4: Depth-First Search (DFS)
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Graph traversal using recursion/stack

### Description
Implement DFS traversal on an undirected graph starting from a given node.

### Input Specification
- First line: Two integers n and e (1 ≤ n ≤ 100, 0 ≤ e ≤ 1000)
- Next e lines: Two integers u and v representing an edge
- Last line: Starting node for DFS

### Output Specification
- Print the DFS traversal order (space-separated node numbers)
- When multiple nodes can be visited, choose the smaller numbered node first

### Test Cases

**Test Case 1:**
```
Input:
5 6
0 1
0 2
1 3
1 4
2 4
3 4
0
Output: 0 1 3 4 2
```

**Test Case 2:**
```
Input:
4 3
0 1
1 2
2 3
0
Output: 0 1 2 3
```

---

## Problem 5: Longest Common Subsequence
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Dynamic programming

### Description
Find the length of the longest common subsequence (LCS) between two strings.

### Input Specification
- First line: A string s1 (1 ≤ length ≤ 100)
- Second line: A string s2 (1 ≤ length ≤ 100)

### Output Specification
- Print the length of the LCS

### Test Cases

**Test Case 1:**
```
Input:
ABCDGH
AEDFHR
Output: 3
```
(LCS is "ADH")

**Test Case 2:**
```
Input:
AGGTAB
GXTXAYB
Output: 4
```
(LCS is "GTAB")
