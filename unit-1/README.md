
# Lab 01 – Introduction to Arrays

## Subject
Data Structures (DS)

## Unit
Unit 1 – Introduction to Arrays

## Overview
This lab contains four C++ programs based on one-dimensional arrays, two-dimensional arrays, sparse matrices and matrix operations.

## Programs

### 1. Array Operations
**Problem Statement:** Perform insertion, deletion, searching, updating and displaying operations on a one-dimensional array.

**Approach:** Used array traversal and functions to perform different operations.

**Complexity:**
- Insertion: O(n)
- Deletion: O(n)
- Searching: O(n)
- Updating: O(1)
- Display: O(n)

**Sample Input:**
Array: 10 20 30 40

Insert 25 at position 3.

**Sample Output:**
10 20 25 30 40

**Learning Outcomes:** Understanding array manipulation and indexing.

### 2. 2D Array Operations
**Problem Statement:** Perform addition, subtraction, multiplication and transpose on matrices.

**Approach:** Used nested loops and two-dimensional arrays.

**Complexity:**
- Addition: O(r*c)
- Subtraction: O(r*c)
- Multiplication: O(r1*c1*c2)
- Transpose: O(r*c)

**Sample Input:**
A = 1 2
    3 4

B = 5 6
    7 8

**Sample Output:**
Addition:
6 8
10 12

**Learning Outcomes:** Understanding matrices and nested loops.

### 3. Sparse Matrix
**Problem Statement:** Represent a sparse matrix using triplet representation and calculate its transpose.

**Approach:** Store only non-zero elements along with their row and column positions.

**Complexity:**
- Triplet conversion: O(r*c)
- Transpose: O(c*k)

**Sample Input:**
0 0 3
0 0 0
0 5 0

**Sample Output:**
3 3 2
0 2 3
2 1 5

**Learning Outcomes:** Understanding sparse matrix representation and memory optimization.

### 4. Matrix Calculator
**Problem Statement:** Create a menu-driven matrix calculator.

**Approach:** Used modular functions and switch-case statements.

**Complexity:**
- Addition: O(r*c)
- Subtraction: O(r*c)
- Multiplication: O(r1*c1*c2)
- Transpose: O(r*c)

**Learning Outcomes:** Understanding matrix calculations and modular programming.

## Technologies Used
- Programming Language: C++
- IDE: Visual Studio Code
- Version Control: Git
- Repository Hosting: GitHub

## Screenshots
Program execution screenshots are available in individual program folders.

## Conclusion
This lab helped develop an understanding of arrays, matrix operations, sparse matrix representation, algorithm complexity and modular programming.
