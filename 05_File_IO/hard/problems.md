# File I/O - Hard Problems

## Problem 1: Binary File Handler
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Binary file operations and data serialization

### Description
Read and write structured data to a binary file using pickle module.

### Input Specification
- First line: Operation ("write" or "read")
- For write operation:
  - Second line: Filename (string)
  - Third line: Number of records n (1 ≤ n ≤ 100)
  - Next n lines: name,age,score (comma-separated)
- For read operation:
  - Second line: Filename (string)

### Output Specification
- For write: Print "Data written successfully"
- For read: Print each record in format "name: age, score"

### Test Cases

**Test Case 1:**
```
Input:
write
students.dat
2
Alice,20,85
Bob,22,90
Output: Data written successfully
```

**Test Case 2:**
```
Input:
read
students.dat
(Reading file from Test Case 1)
Output:
Alice: 20, 85
Bob: 22, 90
```

---

## Problem 2: Large File Processing
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Efficient processing of large files line by line

### Description
Process a large file line by line and calculate statistics without loading entire file into memory.

### Input Specification
- First line: Filename (string)
- File contains one integer per line

### Output Specification
- First line: Total count of numbers
- Second line: Sum of all numbers
- Third line: Average rounded to 2 decimal places

### Test Cases

**Test Case 1:**
```
Input: numbers.txt
(numbers.txt contains:
10
20
30
40
50)
Output:
5
150
30.00
```

**Test Case 2:**
```
Input: values.txt
(values.txt contains:
100
200
300)
Output:
3
600
200.00
```

---

## Problem 3: Directory Walker
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** File system traversal and filtering

### Description
Walk through a directory and count files by extension.

### Input Specification
- First line: Directory path (string)
- Second line: File extension to count (e.g., ".txt", ".py")

### Output Specification
- Print the count of files with specified extension
- Include files in subdirectories

### Test Cases

**Test Case 1:**
```
Input:
./project
.py
(project directory has 5 .py files in various subdirectories)
Output: 5
```

**Test Case 2:**
```
Input:
./docs
.md
(docs directory has 3 .md files)
Output: 3
```

---

## Problem 4: File Merge and Sort
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** Multiple file handling and data merging

### Description
Read multiple sorted files, merge their contents, and write a single sorted output file.

### Input Specification
- First line: Number of input files n (2 ≤ n ≤ 10)
- Next n lines: Input filenames
- Last line: Output filename
- Each input file contains sorted integers (one per line)

### Output Specification
- Create merged sorted output file
- Print "Files merged successfully"

### Test Cases

**Test Case 1:**
```
Input:
2
file1.txt
file2.txt
merged.txt
(file1.txt: 1,3,5; file2.txt: 2,4,6)
Output: Files merged successfully
(merged.txt will contain: 1,2,3,4,5,6)
```

**Test Case 2:**
```
Input:
3
a.txt
b.txt
c.txt
result.txt
(a.txt: 10,30; b.txt: 20,40; c.txt: 15,35)
Output: Files merged successfully
```

---

## Problem 5: File Encryption/Decryption
**Type:** Implementation  
**Estimated Time:** 20 minutes  
**Concept Focus:** File manipulation with basic encryption

### Description
Implement simple Caesar cipher encryption/decryption for text files.

### Input Specification
- First line: Operation ("encrypt" or "decrypt")
- Second line: Input filename (string)
- Third line: Output filename (string)
- Fourth line: Shift value (integer, 1 ≤ shift ≤ 25)

### Output Specification
- Create output file with encrypted/decrypted content
- Print "Operation completed successfully"
- Only alphabetic characters are shifted, preserve case

### Test Cases

**Test Case 1:**
```
Input:
encrypt
plain.txt
encrypted.txt
3
(plain.txt contains: "Hello World")
Output: Operation completed successfully
(encrypted.txt will contain: "Khoor Zruog")
```

**Test Case 2:**
```
Input:
decrypt
encrypted.txt
decrypted.txt
3
(encrypted.txt contains: "Khoor Zruog")
Output: Operation completed successfully
(decrypted.txt will contain: "Hello World")
```
