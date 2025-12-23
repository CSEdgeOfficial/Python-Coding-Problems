# Data Structures - Medium Problems

## Problem 1: Dictionary Merger
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** Dictionaries and merging logic

### Description
Merge two dictionaries. If a key exists in both, sum their values.

### Input Specification
- First line: An integer n1 (0 ≤ n1 ≤ 50) - number of key-value pairs in first dictionary
- Next n1 lines: key value pairs (space-separated)
- Next line: An integer n2 (0 ≤ n2 ≤ 50) - number of key-value pairs in second dictionary
- Next n2 lines: key value pairs (space-separated)
- Keys are strings, values are integers

### Output Specification
- Print the merged dictionary in the format "key: value" sorted by key alphabetically
- One pair per line

### Test Cases

**Test Case 1:**
```
Input:
2
a 10
b 20
2
b 5
c 15
Output:
a: 10
b: 25
c: 15
```

**Test Case 2:**
```
Input:
1
x 100
1
y 200
Output:
x: 100
y: 200
```

---

## Problem 2: Set Operations
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** Sets and set operations

### Description
Perform union, intersection, and difference operations on two sets.

### Input Specification
- First line: An integer n1 (1 ≤ n1 ≤ 50)
- Second line: n1 space-separated integers (first set)
- Third line: An integer n2 (1 ≤ n2 ≤ 50)
- Fourth line: n2 space-separated integers (second set)

### Output Specification
- First line: Union of sets (sorted, space-separated)
- Second line: Intersection of sets (sorted, space-separated)
- Third line: Difference (set1 - set2) (sorted, space-separated)

### Test Cases

**Test Case 1:**
```
Input:
4
1 2 3 4
3
3 4 5
Output:
1 2 3 4 5
3 4
1 2
```

**Test Case 2:**
```
Input:
3
10 20 30
2
20 40
Output:
10 20 30 40
20
10 30
```

---

## Problem 3: Stack Implementation
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Stack data structure using lists

### Description
Implement basic stack operations: push, pop, and peek.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100) - number of operations
- Next n lines: Operations in format:
  - "push x" - push integer x onto stack
  - "pop" - remove top element
  - "peek" - view top element

### Output Specification
- For each "peek" operation, print the top element
- For each "pop" operation, print "Empty" if stack is empty, otherwise print the popped element
- For "push" operations, no output

### Test Cases

**Test Case 1:**
```
Input:
5
push 10
push 20
peek
pop
peek
Output:
20
20
10
```

**Test Case 2:**
```
Input:
3
push 5
pop
pop
Output:
5
Empty
```

---

## Problem 4: Queue Implementation
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Queue data structure using lists

### Description
Implement basic queue operations: enqueue, dequeue, and front.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100) - number of operations
- Next n lines: Operations in format:
  - "enqueue x" - add integer x to queue
  - "dequeue" - remove front element
  - "front" - view front element

### Output Specification
- For each "front" operation, print the front element or "Empty"
- For each "dequeue" operation, print the dequeued element or "Empty"
- For "enqueue" operations, no output

### Test Cases

**Test Case 1:**
```
Input:
5
enqueue 1
enqueue 2
front
dequeue
front
Output:
1
1
2
```

**Test Case 2:**
```
Input:
2
dequeue
enqueue 10
Output:
Empty
```

---

## Problem 5: Frequency Dictionary
**Type:** Implementation  
**Estimated Time:** 15 minutes  
**Concept Focus:** Dictionaries and counting

### Description
Create a frequency dictionary that counts occurrences of each element in a list.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 100)
- Second line: n space-separated integers

### Output Specification
- Print each unique element and its frequency in the format "element: count"
- Sort by element value in ascending order

### Test Cases

**Test Case 1:**
```
Input:
7
1 2 2 3 3 3 4
Output:
1: 1
2: 2
3: 3
4: 1
```

**Test Case 2:**
```
Input:
5
5 5 5 5 5
Output:
5: 5
```
