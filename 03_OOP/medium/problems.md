# OOP - Medium Problems

## Problem 1: Inheritance
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** Class inheritance and method overriding

### Description
Create a base class `Shape` with a method `area()`. Create derived classes `Circle` and `Square` that inherit from `Shape` and implement their own `area()` method.

### Input Specification
- First line: Shape type ("circle" or "square")
- Second line: 
  - For circle: radius (float, 0 < radius ≤ 100)
  - For square: side length (float, 0 < side ≤ 100)

### Output Specification
- Print the area rounded to 2 decimal places
- Use π = 3.14159

### Test Cases

**Test Case 1:**
```
Input:
circle
5.0
Output: 78.54
```

**Test Case 2:**
```
Input:
square
4.0
Output: 16.00
```

---

## Problem 2: Encapsulation
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** Private attributes and getter/setter methods

### Description
Create a `Student` class with private attributes for name and grade. Implement getter and setter methods with validation (grade must be 0-100).

### Input Specification
- First line: Student name (string)
- Second line: Initial grade (integer, 0 ≤ grade ≤ 100)
- Third line: An integer n (1 ≤ n ≤ 10) - number of operations
- Next n lines: Operations:
  - "get_name" - print name
  - "get_grade" - print grade
  - "set_grade x" - set grade to x (with validation)

### Output Specification
- For "get_name", print the name
- For "get_grade", print the grade
- For "set_grade" with invalid value (< 0 or > 100), print "Invalid grade"
- For valid "set_grade", no output

### Test Cases

**Test Case 1:**
```
Input:
Alice
85
3
get_grade
set_grade 90
get_grade
Output:
85
90
```

**Test Case 2:**
```
Input:
Bob
75
2
set_grade 150
get_grade
Output:
Invalid grade
75
```

---

## Problem 3: Polymorphism
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Method overriding and polymorphic behavior

### Description
Create an `Animal` base class with a `speak()` method. Create `Dog` and `Cat` classes that override `speak()` with appropriate sounds.

### Input Specification
- First line: Number of animals n (1 ≤ n ≤ 10)
- Next n lines: Animal type ("dog" or "cat")

### Output Specification
- For each animal, print the sound it makes:
  - Dog: "Woof!"
  - Cat: "Meow!"

### Test Cases

**Test Case 1:**
```
Input:
3
dog
cat
dog
Output:
Woof!
Meow!
Woof!
```

**Test Case 2:**
```
Input:
2
cat
cat
Output:
Meow!
Meow!
```

---

## Problem 4: Class Composition
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Object composition (has-a relationship)

### Description
Create an `Engine` class and a `Car` class where Car has an Engine. Implement methods to start/stop the engine and drive.

### Input Specification
- First line: Engine horsepower (integer, 0 < hp ≤ 1000)
- Second line: An integer n (1 ≤ n ≤ 10) - number of operations
- Next n lines: Operations:
  - "start" - start engine
  - "stop" - stop engine
  - "drive" - attempt to drive (only works if engine is running)
  - "status" - check if engine is running

### Output Specification
- "start": Print "Engine started"
- "stop": Print "Engine stopped"
- "drive": Print "Car is driving" or "Cannot drive, engine is off"
- "status": Print "Engine is running" or "Engine is off"

### Test Cases

**Test Case 1:**
```
Input:
200
4
start
drive
stop
drive
Output:
Engine started
Car is driving
Engine stopped
Cannot drive, engine is off
```

**Test Case 2:**
```
Input:
150
2
drive
status
Output:
Cannot drive, engine is off
Engine is off
```

---

## Problem 5: Static and Class Methods
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** @staticmethod and @classmethod decorators

### Description
Create a `Counter` class with a class variable to count instances. Implement static method for validation and class method to get count.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 20) - number of operations
- Next n lines: Operations:
  - "create" - create new Counter instance
  - "count" - get total number of instances created
  - "validate x" - check if x is positive (static method)

### Output Specification
- "create": No output
- "count": Print the total count
- "validate x": Print "Valid" if x > 0, otherwise "Invalid"

### Test Cases

**Test Case 1:**
```
Input:
5
create
create
count
validate 10
validate -5
Output:
2
Valid
Invalid
```

**Test Case 2:**
```
Input:
3
count
create
count
Output:
0
1
```
