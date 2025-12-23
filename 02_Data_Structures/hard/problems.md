# Data Structures - Hard Problems

## Problem 1: Linked List Implementation
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Linked list node structure and operations

### Description
Implement a simple singly linked list with insert, delete, and display operations.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100) - number of operations
- Next n lines: Operations in format:
  - "insert x" - insert integer x at the end
  - "delete x" - delete first occurrence of x
  - "display" - show all elements

### Output Specification
- For each "display" operation, print all elements separated by spaces, or "Empty" if list is empty
- For "delete" operation, print "Not Found" if element doesn't exist, otherwise no output
- For "insert" operations, no output

### Test Cases

**Test Case 1:**
```
Input:
6
insert 10
insert 20
insert 30
display
delete 20
display
Output:
10 20 30
10 30
```

**Test Case 2:**
```
Input:
3
insert 5
delete 10
display
Output:
Not Found
5
```

---

## Problem 2: Binary Tree Traversal
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Tree structure and traversal algorithms

### Description
Given a binary tree represented as a dictionary, perform inorder, preorder, and postorder traversals.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 50) - number of nodes
- Next n lines: "node left_child right_child" (use -1 for no child)
- Last line: root node value

### Output Specification
- First line: Inorder traversal (space-separated)
- Second line: Preorder traversal (space-separated)
- Third line: Postorder traversal (space-separated)

### Test Cases

**Test Case 1:**
```
Input:
3
1 2 3
2 -1 -1
3 -1 -1
1
Output:
2 1 3
1 2 3
2 3 1
```

**Test Case 2:**
```
Input:
5
1 2 3
2 4 5
3 -1 -1
4 -1 -1
5 -1 -1
1
Output:
4 2 5 1 3
1 2 4 5 3
4 5 2 3 1
```

---

## Problem 3: Graph Representation
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Graph data structure using adjacency list

### Description
Create an adjacency list representation of a directed graph and find all neighbors of a given node.

### Input Specification
- First line: Two integers n and e (1 ≤ n ≤ 100, 0 ≤ e ≤ 1000) - nodes and edges
- Next e lines: Two integers u and v representing edge from u to v
- Last line: An integer q - query node

### Output Specification
- Print all neighbors of node q in ascending order, space-separated
- Print "No neighbors" if node has no outgoing edges

### Test Cases

**Test Case 1:**
```
Input:
4 4
1 2
1 3
2 4
3 4
1
Output:
2 3
```

**Test Case 2:**
```
Input:
3 2
1 2
2 3
3
Output:
No neighbors
```

---

## Problem 4: Priority Queue
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Heap/priority queue operations

### Description
Implement a min-priority queue that supports insert and extract-min operations.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100) - number of operations
- Next n lines: Operations in format:
  - "insert x" - insert integer x
  - "extract" - remove and return minimum element

### Output Specification
- For each "extract" operation, print the minimum element or "Empty"
- For "insert" operations, no output

### Test Cases

**Test Case 1:**
```
Input:
6
insert 5
insert 2
insert 8
extract
extract
extract
Output:
2
5
8
```

**Test Case 2:**
```
Input:
4
insert 10
extract
extract
insert 3
Output:
10
Empty
```

---

## Problem 5: LRU Cache
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Hash map and doubly linked list combination

### Description
Implement a Least Recently Used (LRU) cache with get and put operations. The cache has a fixed capacity.

### Input Specification
- First line: An integer capacity (1 ≤ capacity ≤ 100)
- Second line: An integer n (1 ≤ n ≤ 100) - number of operations
- Next n lines: Operations in format:
  - "put key value" - insert or update key-value pair
  - "get key" - retrieve value for key

### Output Specification
- For each "get" operation, print the value or "-1" if key doesn't exist
- For "put" operations, no output

### Test Cases

**Test Case 1:**
```
Input:
2
4
put 1 10
put 2 20
get 1
put 3 30
Output:
10
```

**Test Case 2:**
```
Input:
2
5
put 1 100
put 2 200
get 1
put 3 300
get 2
Output:
100
-1
```
(After putting 3, key 2 is evicted as it was least recently used)
