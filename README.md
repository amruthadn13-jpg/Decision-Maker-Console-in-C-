# Decision Maker Console in C++

## Overview

This project is a C++ console application that demonstrates the use of conditional statements and switch-case control structures.

The program performs three practical tasks:

1. Checks voting eligibility based on age
2. Assigns grades based on marks
3. Performs arithmetic operations using a menu-driven calculator

---

## Concepts Covered

* `if`, `else if`, and `else` statements
* `switch` statement
* Relational operators
* Arithmetic operators
* User input and output
* Basic error handling

---

## Project Description

### Voting Eligibility Checker

The program asks the user to enter their age and determines whether they are eligible to vote.

* Age 18 or above → Eligible to vote
* Age below 18 → Not eligible to vote

### Grade Classification

The program takes marks as input and assigns a grade.

* 90 and above → Grade A
* 75 to 89 → Grade B
* 50 to 74 → Grade C
* Below 50 → Fail

### Menu-Driven Calculator

The user enters two numbers and selects an operation from a menu.

Available operations:

* Addition
* Subtraction
* Multiplication
* Division

The calculator uses a `switch` statement to perform the selected operation. Division by zero is handled safely.

---

## Sample Output

```text id="8j6wfr"
========== Decision Maker Console ==========

Enter your age: 21
You are eligible to vote.

Enter your marks: 82
Grade: B

Enter two numbers: 10 5

Calculator Menu
1. Addition
2. Subtraction
3. Multiplication
4. Division
Enter your choice: 3
Result: 50
```

---

## Learning Outcomes

* Writing decision-making logic in C++
* Using multiple conditional branches
* Implementing menu-based programs
* Handling invalid choices and division by zero

---

## Real-World Applications

* Eligibility verification systems
* Student grading software
* Calculator programs
* Command-line utility tools

---

## Author

Amrutha D N
