# OOP - Hard Problems

## Problem 1: Multiple Inheritance
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Multiple inheritance and method resolution order

### Description
Create classes `Flyer` and `Swimmer` with their respective methods. Create a `Duck` class that inherits from both and implements all methods.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 10) - number of operations
- Next n lines: Operations:
  - "fly" - make the duck fly
  - "swim" - make the duck swim
  - "quack" - make the duck quack (unique to Duck)

### Output Specification
- "fly": Print "Flying in the sky"
- "swim": Print "Swimming in water"
- "quack": Print "Quack quack!"

### Test Cases

**Test Case 1:**
```
Input:
4
fly
swim
quack
fly
Output:
Flying in the sky
Swimming in water
Quack quack!
Flying in the sky
```

**Test Case 2:**
```
Input:
2
quack
swim
Output:
Quack quack!
Swimming in water
```

---

## Problem 2: Abstract Base Classes
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** ABC module and abstract methods

### Description
Create an abstract `Vehicle` class with abstract methods `start()` and `stop()`. Implement concrete classes `Car` and `Motorcycle`.

### Input Specification
- First line: Vehicle type ("car" or "motorcycle")
- Second line: An integer n (1 ≤ n ≤ 10) - number of operations
- Next n lines: Operations ("start" or "stop")

### Output Specification
- For car:
  - "start": Print "Car engine started"
  - "stop": Print "Car engine stopped"
- For motorcycle:
  - "start": Print "Motorcycle engine started"
  - "stop": Print "Motorcycle engine stopped"

### Test Cases

**Test Case 1:**
```
Input:
car
3
start
stop
start
Output:
Car engine started
Car engine stopped
Car engine started
```

**Test Case 2:**
```
Input:
motorcycle
2
start
stop
Output:
Motorcycle engine started
Motorcycle engine stopped
```

---

## Problem 3: Operator Overloading
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Magic methods for operator overloading

### Description
Create a `Vector2D` class representing 2D vectors. Implement __add__, __sub__, and __str__ methods for vector operations.

### Input Specification
- First line: Two floats separated by space (x1, y1) - first vector
- Second line: Two floats separated by space (x2, y2) - second vector
- Third line: Operation ("add" or "subtract")

### Output Specification
- Print the resulting vector in format "(x, y)" with values rounded to 2 decimal places

### Test Cases

**Test Case 1:**
```
Input:
1.0 2.0
3.0 4.0
add
Output: (4.00, 6.00)
```

**Test Case 2:**
```
Input:
5.5 7.5
2.5 3.5
subtract
Output: (3.00, 4.00)
```

---

## Problem 4: Design Pattern - Singleton
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Singleton design pattern implementation

### Description
Implement a Singleton `Database` class that ensures only one instance exists. Include a method to store and retrieve data.

### Input Specification
- First line: An integer n (1 ≤ n ≤ 20) - number of operations
- Next n lines: Operations:
  - "set key value" - store key-value pair
  - "get key" - retrieve value for key
  - "instance_id" - print id of current instance

### Output Specification
- "set": No output
- "get": Print the value or "Not found"
- "instance_id": Print a consistent ID showing same instance is used

### Test Cases

**Test Case 1:**
```
Input:
5
set name Python
get name
instance_id
get age
instance_id
Output:
Python
12345
Not found
12345
```
(Note: The actual ID will vary, but should be consistent)

**Test Case 2:**
```
Input:
3
set x 100
get x
get y
Output:
100
Not found
```

---

## Problem 5: Property Decorators
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** @property decorator for getters and setters

### Description
Create a `Temperature` class that stores temperature in Celsius but provides properties to get/set in Fahrenheit and Kelvin.

### Input Specification
- First line: Initial temperature in Celsius (float, -273.15 ≤ temp ≤ 1000)
- Second line: An integer n (1 ≤ n ≤ 10) - number of operations
- Next n lines: Operations:
  - "get_celsius" - get temperature in Celsius
  - "get_fahrenheit" - get temperature in Fahrenheit
  - "get_kelvin" - get temperature in Kelvin
  - "set_celsius x" - set temperature in Celsius
  - "set_fahrenheit x" - set temperature in Fahrenheit

### Output Specification
- For get operations, print temperature rounded to 2 decimal places
- For set operations, no output

### Formulas
- Fahrenheit = (Celsius × 9/5) + 32
- Kelvin = Celsius + 273.15

### Test Cases

**Test Case 1:**
```
Input:
0
3
get_celsius
get_fahrenheit
get_kelvin
Output:
0.00
32.00
273.15
```

**Test Case 2:**
```
Input:
25
4
set_fahrenheit 212
get_celsius
get_kelvin
get_fahrenheit
Output:
100.00
373.15
212.00
```
