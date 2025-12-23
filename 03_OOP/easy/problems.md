# OOP - Easy Problems

## Problem 1: Simple Class
**Type:** Implementation  
**Estimated Time:** 10 minutes  
**Concept Focus:** Basic class definition and instance creation

### Description
Create a `Person` class with attributes name and age, and a method to display the information.

### Input Specification
- First line: A string (name)
- Second line: An integer (age, 0 ≤ age ≤ 150)

### Output Specification
- Print "Name: [name], Age: [age]"

### Test Cases

**Test Case 1:**
```
Input:
Alice
25
Output: Name: Alice, Age: 25
```

**Test Case 2:**
```
Input:
Bob
30
Output: Name: Bob, Age: 30
```

---

## Problem 2: Class with Constructor
**Type:** Implementation  
**Estimated Time:** 10-15 minutes  
**Concept Focus:** __init__ constructor method

### Description
Create a `Rectangle` class with width and height attributes. Include a method to calculate area.

### Input Specification
- First line: A float (width, 0 < width ≤ 1000)
- Second line: A float (height, 0 < height ≤ 1000)

### Output Specification
- Print the area rounded to 2 decimal places

### Test Cases

**Test Case 1:**
```
Input:
5
10
Output: 50.00
```

**Test Case 2:**
```
Input:
3.5
4.2
Output: 14.70
```

---

## Problem 3: Class Methods
**Type:** Implementation  
**Estimated Time:** 15 minutes  
**Concept Focus:** Instance methods and self parameter

### Description
Create a `BankAccount` class with methods to deposit, withdraw, and check balance.

### Input Specification
- First line: Initial balance (float, balance ≥ 0)
- Second line: An integer n (1 ≤ n ≤ 10) - number of operations
- Next n lines: Operations in format:
  - "deposit x" - deposit amount x
  - "withdraw x" - withdraw amount x (only if sufficient balance)
  - "balance" - check current balance

### Output Specification
- For "balance" operation, print current balance rounded to 2 decimal places
- For "withdraw" operation with insufficient funds, print "Insufficient funds"
- For "deposit" and successful "withdraw", no output

### Test Cases

**Test Case 1:**
```
Input:
100.0
4
deposit 50.0
balance
withdraw 30.0
balance
Output:
150.00
120.00
```

**Test Case 2:**
```
Input:
50.0
2
withdraw 100.0
balance
Output:
Insufficient funds
50.00
```

---

## Problem 4: String Representation
**Type:** Implementation  
**Estimated Time:** 10-15 minutes  
**Concept Focus:** __str__ method

### Description
Create a `Book` class with title and author attributes. Implement __str__ method for nice string representation.

### Input Specification
- First line: Book title (string)
- Second line: Author name (string)

### Output Specification
- Print "[title] by [author]"

### Test Cases

**Test Case 1:**
```
Input:
Python Programming
John Smith
Output: Python Programming by John Smith
```

**Test Case 2:**
```
Input:
Data Structures
Jane Doe
Output: Data Structures by Jane Doe
```

---

## Problem 5: Class with Multiple Methods
**Type:** Implementation  
**Estimated Time:** 15 minutes  
**Concept Focus:** Multiple methods in a class

### Description
Create a `Calculator` class with methods for addition, subtraction, multiplication, and division.

### Input Specification
- First line: Two floats separated by space (operand1, operand2)
- Second line: Operation ("add", "subtract", "multiply", "divide")

### Output Specification
- Print the result rounded to 2 decimal places
- For division by zero, print "Cannot divide by zero"

### Test Cases

**Test Case 1:**
```
Input:
10.0 5.0
add
Output: 15.00
```

**Test Case 2:**
```
Input:
20.0 4.0
divide
Output: 5.00
```
