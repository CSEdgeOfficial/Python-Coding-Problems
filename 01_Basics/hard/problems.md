# Basics - Hard Problems

## Problem 1: Number Pattern Generator
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Nested loops and pattern logic

### Description
Generate a pyramid pattern of numbers where each row contains numbers from 1 to the row number, repeated twice (ascending then descending).

### Input Specification
- A single integer n (1 ≤ n ≤ 9) representing the number of rows

### Output Specification
- Print n rows where row i contains numbers from 1 to i and back down to 1
- Numbers in each row are separated by spaces

### Test Cases

**Test Case 1:**
```
Input: 3
Output:
1
1 2 1
1 2 3 2 1
```

**Test Case 2:**
```
Input: 5
Output:
1
1 2 1
1 2 3 2 1
1 2 3 4 3 2 1
1 2 3 4 5 4 3 2 1
```

---

## Problem 2: Roman Numeral Converter
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** String manipulation and mapping logic

### Description
Convert a decimal number to Roman numerals. Use standard Roman numeral symbols: I(1), V(5), X(10), L(50), C(100), D(500), M(1000).

### Input Specification
- A single integer n (1 ≤ n ≤ 3999)

### Output Specification
- Print the Roman numeral representation

### Test Cases

**Test Case 1:**
```
Input: 58
Output: LVIII
```

**Test Case 2:**
```
Input: 1994
Output: MCMXCIV
```

---

## Problem 3: Word Frequency Counter
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** String parsing and dictionaries

### Description
Count the frequency of each word in a sentence and display them in alphabetical order.

### Input Specification
- A single line containing a sentence (1-200 characters)
- Words are separated by spaces
- Convert all words to lowercase
- Ignore punctuation

### Output Specification
- Print each unique word and its frequency in the format "word: count"
- Sort output alphabetically by word

### Test Cases

**Test Case 1:**
```
Input: hello world hello
Output:
hello: 2
world: 1
```

**Test Case 2:**
```
Input: The quick brown fox jumps over the lazy dog
Output:
brown: 1
dog: 1
fox: 1
jumps: 1
lazy: 1
over: 1
quick: 1
the: 2
```

---

## Problem 4: Armstrong Number Checker
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** Mathematical operations and digit manipulation

### Description
Check if a number is an Armstrong number. An Armstrong number is a number that is equal to the sum of its own digits each raised to the power of the number of digits.

### Input Specification
- A single integer n (1 ≤ n ≤ 100000)

### Output Specification
- Print "Armstrong" if the number is an Armstrong number
- Print "Not Armstrong" otherwise

### Test Cases

**Test Case 1:**
```
Input: 153
Output: Armstrong
```
(Explanation: 153 = 1³ + 5³ + 3³ = 1 + 125 + 27)

**Test Case 2:**
```
Input: 123
Output: Not Armstrong
```

---

## Problem 5: GCD and LCM Calculator
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Mathematical algorithms (Euclidean algorithm)

### Description
Calculate both the Greatest Common Divisor (GCD) and Least Common Multiple (LCM) of two numbers.

### Input Specification
- First line: An integer a (1 ≤ a ≤ 10000)
- Second line: An integer b (1 ≤ b ≤ 10000)

### Output Specification
- First line: GCD of a and b
- Second line: LCM of a and b

### Test Cases

**Test Case 1:**
```
Input:
12
18
Output:
6
36
```

**Test Case 2:**
```
Input:
7
13
Output:
1
91
```
