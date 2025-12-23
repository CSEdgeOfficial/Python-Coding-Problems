# File I/O - Medium Problems

## Problem 1: Word Count in File
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** File reading and string processing

### Description
Count the total number of words in a text file.

### Input Specification
- First line: Filename (string)
- File contains text with words separated by spaces

### Output Specification
- Print the total word count

### Test Cases

**Test Case 1:**
```
Input: document.txt
(document.txt contains: "The quick brown fox jumps over the lazy dog")
Output: 9
```

**Test Case 2:**
```
Input: story.txt
(story.txt contains: "Hello World\nPython Programming")
Output: 4
```

---

## Problem 2: CSV File Parser
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Parsing structured file formats

### Description
Read a CSV file and calculate the average of values in a specified column.

### Input Specification
- First line: CSV filename (string)
- Second line: Column index (0-based integer)
- CSV file format: comma-separated values, first row is header
- Column contains numeric values

### Output Specification
- Print the average rounded to 2 decimal places

### Test Cases

**Test Case 1:**
```
Input:
data.csv
1
(data.csv contains:
Name,Score,Grade
Alice,85,A
Bob,92,A
Charlie,78,B)
Output: 85.00
```

**Test Case 2:**
```
Input:
sales.csv
2
(sales.csv contains:
Product,Price,Quantity
Apple,1.5,100
Banana,0.5,200
Orange,2.0,150)
Output: 150.00
```

---

## Problem 3: File Search and Replace
**Type:** Implementation  
**Estimated Time:** 15-20 minutes  
**Concept Focus:** Text processing and file modification

### Description
Search for a word in a file and replace all occurrences with another word.

### Input Specification
- First line: Filename (string)
- Second line: Search word (string)
- Third line: Replace word (string)

### Output Specification
- Create a new file with "_modified" suffix
- Print the number of replacements made

### Test Cases

**Test Case 1:**
```
Input:
text.txt
hello
hi
(text.txt contains: "hello world hello")
Output: 2
```

**Test Case 2:**
```
Input:
doc.txt
Python
Java
(doc.txt contains: "Python is great. I love Python.")
Output: 2
```

---

## Problem 4: JSON File Handler
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Working with JSON files

### Description
Read a JSON file, update a specific field, and write back to the file.

### Input Specification
- First line: JSON filename (string)
- Second line: Key to update (string)
- Third line: New value (string)

### Output Specification
- Update the JSON file
- Print "JSON updated successfully"

### Test Cases

**Test Case 1:**
```
Input:
config.json
version
2.0
(config.json contains: {"name": "app", "version": "1.0"})
Output: JSON updated successfully
```

**Test Case 2:**
```
Input:
user.json
age
30
(user.json contains: {"name": "Alice", "age": 25})
Output: JSON updated successfully
```

---

## Problem 5: Log File Analyzer
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** File parsing and data extraction

### Description
Analyze a log file and count occurrences of different log levels (INFO, WARNING, ERROR).

### Input Specification
- First line: Log filename (string)
- Log format: Each line starts with [LEVEL] followed by message
- Example: "[INFO] Application started"

### Output Specification
- Print three lines in format "LEVEL: count"
- Order: INFO, WARNING, ERROR

### Test Cases

**Test Case 1:**
```
Input: app.log
(app.log contains:
[INFO] App started
[ERROR] Connection failed
[INFO] Processing data
[WARNING] Low memory)
Output:
INFO: 2
WARNING: 1
ERROR: 1
```

**Test Case 2:**
```
Input: system.log
(system.log contains:
[INFO] System boot
[INFO] Services started
[ERROR] Disk full)
Output:
INFO: 2
WARNING: 0
ERROR: 1
```
