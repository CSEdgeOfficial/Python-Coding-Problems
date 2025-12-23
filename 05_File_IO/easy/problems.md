# File I/O - Easy Problems

## Problem 1: Read and Display File
**Type:** Implementation  
**Estimated Time:** 10 minutes  
**Concept Focus:** Basic file reading operations

### Description
Read the contents of a text file and display it.

### Input Specification
- First line: Filename (string)
- The file exists in the current directory
- File contains text data (1-1000 characters)

### Output Specification
- Print the entire contents of the file

### Test Cases

**Test Case 1:**
```
Input: sample.txt
(sample.txt contains: "Hello World")
Output: Hello World
```

**Test Case 2:**
```
Input: data.txt
(data.txt contains: "Line 1\nLine 2\nLine 3")
Output:
Line 1
Line 2
Line 3
```

---

## Problem 2: Count Lines in File
**Type:** Implementation  
**Estimated Time:** 10 minutes  
**Concept Focus:** File reading and counting

### Description
Count the number of lines in a text file.

### Input Specification
- First line: Filename (string)
- The file exists and contains text

### Output Specification
- Print the number of lines in the file

### Test Cases

**Test Case 1:**
```
Input: test.txt
(test.txt contains 3 lines)
Output: 3
```

**Test Case 2:**
```
Input: empty.txt
(empty.txt is empty)
Output: 0
```

---

## Problem 3: Write to File
**Type:** Implementation  
**Estimated Time:** 10-15 minutes  
**Concept Focus:** Basic file writing operations

### Description
Write given text to a new file.

### Input Specification
- First line: Output filename (string)
- Second line: An integer n (1 ≤ n ≤ 10)
- Next n lines: Text to write to the file

### Output Specification
- Create the file with the given content
- Print "File created successfully"

### Test Cases

**Test Case 1:**
```
Input:
output.txt
2
Hello
World
Output: File created successfully
```

**Test Case 2:**
```
Input:
numbers.txt
3
1
2
3
Output: File created successfully
```

---

## Problem 4: Append to File
**Type:** Implementation  
**Estimated Time:** 10-15 minutes  
**Concept Focus:** Appending to existing files

### Description
Append new lines to an existing file or create it if it doesn't exist.

### Input Specification
- First line: Filename (string)
- Second line: An integer n (1 ≤ n ≤ 10)
- Next n lines: Text to append

### Output Specification
- Print "Content appended successfully"

### Test Cases

**Test Case 1:**
```
Input:
log.txt
2
Entry 1
Entry 2
Output: Content appended successfully
```

**Test Case 2:**
```
Input:
notes.txt
1
New note
Output: Content appended successfully
```

---

## Problem 5: Copy File Contents
**Type:** Implementation  
**Estimated Time:** 15 minutes  
**Concept Focus:** Reading from one file and writing to another

### Description
Copy the contents of one file to another file.

### Input Specification
- First line: Source filename (string, file exists)
- Second line: Destination filename (string)

### Output Specification
- Print "File copied successfully"

### Test Cases

**Test Case 1:**
```
Input:
source.txt
destination.txt
Output: File copied successfully
```

**Test Case 2:**
```
Input:
original.txt
backup.txt
Output: File copied successfully
```
