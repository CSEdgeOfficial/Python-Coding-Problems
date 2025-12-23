# Algorithms - Hard Problems

## Problem 1: Dijkstra's Algorithm
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Shortest path algorithm with priority queue

### Description
Implement Dijkstra's algorithm to find the shortest path from a source node to all other nodes in a weighted graph.

### Input Specification
- First line: Two integers n and e (1 ≤ n ≤ 100, 0 ≤ e ≤ 1000)
- Next e lines: Three integers u, v, w (edge from u to v with weight w, w > 0)
- Last line: Source node

### Output Specification
- Print n lines, each containing the shortest distance from source to node i (0 to n-1)
- Print "INF" if node is unreachable

### Test Cases

**Test Case 1:**
```
Input:
5 7
0 1 4
0 2 1
1 3 1
2 1 2
2 3 5
3 4 3
1 4 2
0
Output:
0
3
1
4
5
```

**Test Case 2:**
```
Input:
3 2
0 1 5
1 2 3
0
Output:
0
5
8
```

---

## Problem 2: Knapsack Problem
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Dynamic programming optimization

### Description
Solve the 0/1 knapsack problem: maximize value without exceeding weight capacity.

### Input Specification
- First line: Two integers n and W (1 ≤ n ≤ 100, 1 ≤ W ≤ 1000) - items and capacity
- Next n lines: Two integers w and v (weight and value of item)

### Output Specification
- Print the maximum value achievable

### Test Cases

**Test Case 1:**
```
Input:
3 50
10 60
20 100
30 120
Output: 220
```

**Test Case 2:**
```
Input:
4 8
2 3
3 4
4 5
5 6
Output: 9
```

---

## Problem 3: Topological Sort
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Graph algorithms, ordering with dependencies

### Description
Perform topological sort on a directed acyclic graph (DAG).

### Input Specification
- First line: Two integers n and e (1 ≤ n ≤ 100, 0 ≤ e ≤ 1000)
- Next e lines: Two integers u and v (directed edge from u to v)

### Output Specification
- Print one valid topological ordering (space-separated)
- If multiple valid orderings exist, print any one

### Test Cases

**Test Case 1:**
```
Input:
6 6
5 2
5 0
4 0
4 1
2 3
3 1
Output: 4 5 0 2 3 1
```
(Other valid orderings exist)

**Test Case 2:**
```
Input:
4 4
0 1
0 2
1 3
2 3
Output: 0 1 2 3
```
(Or 0 2 1 3)

---

## Problem 4: Maximum Subarray Sum
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** Kadane's algorithm

### Description
Find the contiguous subarray with the maximum sum (Kadane's algorithm).

### Input Specification
- First line: An integer n (1 ≤ n ≤ 10000)
- Second line: n space-separated integers (can be negative)

### Output Specification
- Print the maximum subarray sum

### Test Cases

**Test Case 1:**
```
Input:
9
-2 1 -3 4 -1 2 1 -5 4
Output: 6
```
(Subarray [4, -1, 2, 1])

**Test Case 2:**
```
Input:
5
-1 -2 -3 -4 -5
Output: -1
```

---

## Problem 5: A* Pathfinding
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Heuristic search algorithm

### Description
Implement A* algorithm to find shortest path in a grid from start to goal. Obstacles are marked as walls.

### Input Specification
- First line: Two integers rows and cols (1 ≤ rows, cols ≤ 20)
- Next rows lines: cols characters each ('.' for empty, '#' for wall)
- Next line: Two integers sr and sc (start row and column, 0-indexed)
- Last line: Two integers er and ec (end row and column, 0-indexed)

### Output Specification
- Print the length of shortest path
- Print "-1" if no path exists
- Movement allowed in 4 directions (up, down, left, right)

### Test Cases

**Test Case 1:**
```
Input:
5 5
.....
.###.
.....
.###.
.....
0 0
4 4
Output: 12
```

**Test Case 2:**
```
Input:
3 3
...
.#.
...
0 0
2 2
Output: 4
```
