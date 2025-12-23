# Python Coding Problems

A comprehensive collection of structured Python practice problems organized by category, difficulty level, and type. Perfect for beginners and intermediate programmers looking to improve their Python skills.

## 📁 Repository Structure

```
Python-Coding-Problems/
│
├── 01_Basics/
│   ├── easy/
│   │   ├── problems.md
│   │   └── solutions/
│   ├── medium/
│   │   ├── problems.md
│   │   └── solutions/
│   └── hard/
│       ├── problems.md
│       └── solutions/
│
├── 02_Data_Structures/
│   ├── easy/
│   │   ├── problems.md
│   │   └── solutions/
│   ├── medium/
│   │   ├── problems.md
│   │   └── solutions/
│   └── hard/
│       ├── problems.md
│       └── solutions/
│
├── 03_OOP/
│   ├── easy/
│   │   ├── problems.md
│   │   └── solutions/
│   ├── medium/
│   │   ├── problems.md
│   │   └── solutions/
│   └── hard/
│       ├── problems.md
│       └── solutions/
│
├── 04_Algorithms/
│   ├── easy/
│   │   ├── problems.md
│   │   └── solutions/
│   ├── medium/
│   │   ├── problems.md
│   │   └── solutions/
│   └── hard/
│       ├── problems.md
│       └── solutions/
│
└── 05_File_IO/
    ├── easy/
    │   ├── problems.md
    │   └── solutions/
    ├── medium/
    │   ├── problems.md
    │   └── solutions/
    └── hard/
        ├── problems.md
        └── solutions/
```

## 🎯 Problem Categories

### 1. Basics
Fundamental Python concepts including:
- Input/output operations
- Variables and data types
- Conditional statements
- Loops and iterations
- String manipulation
- Basic mathematical operations

### 2. Data Structures
Working with Python's built-in data structures:
- Lists and tuples
- Dictionaries and sets
- Stacks and queues
- Linked lists
- Trees and graphs
- Advanced data structures

### 3. Object-Oriented Programming (OOP)
Mastering object-oriented concepts:
- Classes and objects
- Inheritance and polymorphism
- Encapsulation and abstraction
- Class methods and static methods
- Property decorators
- Design patterns

### 4. Algorithms
Classic algorithms and problem-solving techniques:
- Searching algorithms
- Sorting algorithms
- Graph traversal (BFS, DFS)
- Dynamic programming
- Greedy algorithms
- Pathfinding algorithms

### 5. File I/O
File handling and data persistence:
- Reading and writing files
- Working with different file formats (CSV, JSON)
- Binary file operations
- File system operations
- Large file processing
- Data serialization

## 📊 Difficulty Levels

- **Easy**: 5-15 minutes solve time | Single concept focus | Basic implementation
- **Medium**: 15-20 minutes solve time | Multiple concepts | Moderate complexity
- **Hard**: 20+ minutes solve time | Advanced concepts | Complex implementation

## 📝 Problem Format

Each problem includes:
- **Type**: Implementation or Debugging
- **Estimated Time**: Expected completion time
- **Concept Focus**: Main concept being tested
- **Description**: Clear problem statement
- **Input Specification**: Detailed input format and constraints
- **Output Specification**: Expected output format
- **Test Cases**: At least 2 test cases with sample inputs and outputs

## 🚀 How to Use This Repository

1. **Choose a Category**: Start with Basics if you're new to Python, or pick any category based on your learning goals
2. **Select Difficulty**: Begin with easy problems and progressively move to harder ones
3. **Read Carefully**: Understand the problem statement, input/output specifications, and constraints
4. **Implement**: Write your solution in Python
5. **Test**: Verify your solution with the provided test cases
6. **Review**: Check the solutions folder (when available) to compare approaches

## 💡 Sample Problems

### Basics - Easy: Hello World
Write a Python program that takes a name as input and prints a greeting message.

**Input**: `Alice`  
**Output**: `Hello, Alice!`

**Concept Focus**: Basic input/output operations  
**Estimated Time**: 5-10 minutes

---

### Basics - Medium: Palindrome Checker
Check if a given string is a palindrome (reads the same forwards and backwards), ignoring spaces, punctuation, and case.

**Input**: `A man a plan a canal Panama`  
**Output**: `Palindrome`

**Concept Focus**: String manipulation and comparison  
**Estimated Time**: 15-20 minutes

---

### Basics - Hard: Roman Numeral Converter
Convert a decimal number to Roman numerals using standard symbols: I(1), V(5), X(10), L(50), C(100), D(500), M(1000).

**Input**: `1994`  
**Output**: `MCMXCIV`

**Concept Focus**: String manipulation and mapping logic  
**Estimated Time**: 20 minutes

---

### Data Structures - Easy: List Sum
Calculate the sum of all elements in a list of integers.

**Input**:
```
5
1 2 3 4 5
```
**Output**: `15`

**Concept Focus**: Lists and basic operations  
**Estimated Time**: 5-10 minutes

---

### Data Structures - Medium: Stack Implementation
Implement basic stack operations: push, pop, and peek using lists.

**Input**:
```
5
push 10
push 20
peek
pop
peek
```
**Output**:
```
20
20
10
```

**Concept Focus**: Stack data structure using lists  
**Estimated Time**: 20 minutes

---

### Data Structures - Hard: Binary Tree Traversal
Given a binary tree represented as input, perform inorder, preorder, and postorder traversals.

**Input**:
```
3
1 2 3
2 -1 -1
3 -1 -1
1
```
**Output**:
```
2 1 3
1 2 3
2 3 1
```

**Concept Focus**: Tree structure and traversal algorithms  
**Estimated Time**: 20 minutes

---

### OOP - Easy: Simple Class
Create a `Person` class with attributes name and age, and a method to display the information.

**Input**:
```
Alice
25
```
**Output**: `Name: Alice, Age: 25`

**Concept Focus**: Basic class definition and instance creation  
**Estimated Time**: 10 minutes

---

### OOP - Medium: Inheritance
Create a base class `Shape` with an `area()` method. Create derived classes `Circle` and `Square` that implement their own `area()` method.

**Input**:
```
circle
5.0
```
**Output**: `78.54`

**Concept Focus**: Class inheritance and method overriding  
**Estimated Time**: 15-20 minutes

---

### OOP - Hard: Abstract Base Classes
Create an abstract `Vehicle` class with abstract methods `start()` and `stop()`. Implement concrete classes `Car` and `Motorcycle`.

**Input**:
```
car
3
start
stop
start
```
**Output**:
```
Car engine started
Car engine stopped
Car engine started
```

**Concept Focus**: ABC module and abstract methods  
**Estimated Time**: 20 minutes

---

### Algorithms - Easy: Linear Search
Implement linear search to find the index of a target element in a list.

**Input**:
```
5
10 20 30 40 50
30
```
**Output**: `2`

**Concept Focus**: Linear search algorithm  
**Estimated Time**: 10 minutes

---

### Algorithms - Medium: Merge Sort
Implement merge sort to sort an array of integers in ascending order using divide and conquer approach.

**Input**:
```
6
38 27 43 3 9 82
```
**Output**: `3 9 27 38 43 82`

**Concept Focus**: Divide and conquer, merge sort algorithm  
**Estimated Time**: 20 minutes

---

### Algorithms - Hard: Dijkstra's Algorithm
Implement Dijkstra's algorithm to find the shortest path from a source node to all other nodes in a weighted graph.

**Input**:
```
5 7
0 1 4
0 2 1
1 3 1
2 1 2
2 3 5
3 4 3
1 4 2
0
```
**Output**:
```
0
3
1
4
5
```

**Concept Focus**: Shortest path algorithm with priority queue  
**Estimated Time**: 20 minutes

---

### File I/O - Easy: Count Lines in File
Count the number of lines in a text file.

**Input**: `test.txt`  
**Output**: `3`

**Concept Focus**: File reading and counting  
**Estimated Time**: 10 minutes

---

### File I/O - Medium: CSV File Parser
Read a CSV file and calculate the average of values in a specified column.

**Input**:
```
data.csv
1
```
(data.csv contains Name,Score,Grade header and data rows)  
**Output**: `85.00`

**Concept Focus**: Parsing structured file formats  
**Estimated Time**: 20 minutes

---

### File I/O - Hard: File Encryption/Decryption
Implement simple Caesar cipher encryption/decryption for text files.

**Input**:
```
encrypt
plain.txt
encrypted.txt
3
```
(plain.txt contains: "Hello World")  
**Output**: `Operation completed successfully`  
(encrypted.txt will contain: "Khoor Zruog")

**Concept Focus**: File manipulation with basic encryption  
**Estimated Time**: 20 minutes

---

## 🤝 Contributing

Contributions are welcome! If you'd like to add more problems or solutions:
1. Follow the existing format
2. Ensure problems are clearly stated with proper I/O specifications
3. Include at least 2 test cases
4. Add solutions in the respective solutions/ folder

## 📄 License

This repository is open source and available for educational purposes.

## 🌟 Tips for Success

1. **Start Simple**: Begin with easy problems to build confidence
2. **Understand Before Coding**: Read the problem carefully and plan your approach
3. **Test Thoroughly**: Always test with the provided test cases and think of edge cases
4. **Time Yourself**: Try to solve within the estimated time to build efficiency
5. **Learn from Solutions**: Compare your solution with others to learn different approaches
6. **Practice Regularly**: Consistency is key to improving programming skills

Happy Coding! 🐍