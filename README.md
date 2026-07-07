# Introduction to Data Structures and Procedural Programming

## Problem 1 – Sum of Distinct Elements

### Description
Given two sets of elements, find the sum of all distinct elements 
(elements that appear in only one of the two sets).

### Example
- Set 1: [3, 1, 7, 9]
- Set 2: [2, 4, 1, 9, 3]
- Distinct elements: 4, 7, 2
- Output: 13

### Approach
- Use two nested loops to compare each element
- If an element from Set 1 is not found in Set 2, add it to sum
- Do the same for Set 2 elements not found in Set 1

---

## Problem 2 – Orthogonal Vectors (Dot Product)

### Description
Check if two vectors are orthogonal using the dot product.
Two vectors are orthogonal if their dot product equals 0.

### Part 1 – Procedure
A procedure `dot_product` that calculates the scalar product
and stores the result in a variable passed by reference.

### Part 2 – Main Algorithm
Reads n pairs of vectors and checks orthogonality
by calling the `dot_product` procedure.

### Part 3 – Function Version
Same algorithm but using a `dot_product` function
that returns the result instead of modifying a parameter.

---

## Concepts Used
- Arrays
- Nested loops
- Procedures vs Functions
- Pass by reference vs Pass by value
