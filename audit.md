# README.md Audit Report — Python Programming Collection

## 1. Project Description and General Features

| Claim | Verdict | Evidence |
|---|---|---|
| Collection contains three Python programs | Supported | The three source files implement factorial, Fibonacci, and student dictionary examples. |
| Programs practice Python fundamentals | Supported | The programs use variables, loops, arithmetic operations, and dictionaries. |
| Programs improve logical thinking | Not Verifiable | This is a learning benefit, not a functionality demonstrated directly by the code. |
| Programs explore basic programming concepts | Supported | Each program demonstrates basic Python constructs. |
| Programs are beginner-friendly | Not Verifiable | The code is simple, but the intended audience is not established by the code. |
| Code is simple and understandable | Not Verifiable | Understandability is subjective and cannot be confirmed as a functional claim. |
| Programs demonstrate basic problem-solving | Supported | The programs implement factorial calculation, sequence generation, and dictionary access. |

## 2. Factorial Calculator

| Claim | Verdict | Evidence |
|---|---|---|
| Calculates the factorial of a number | Supported | The program multiplies integers from 1 through `n`. |
| Calculates the factorial of a user-provided number | Not Supported | The value `n = 5` is hardcoded; there is no `input()` statement. |
| Uses loops | Supported | A `for` loop calculates the factorial. |
| Uses mathematical operations | Supported | The expression `fact = fact * i` performs multiplication. |
| Provides the calculated result as output | Supported | The program prints the value of `fact`. |

## 3. Fibonacci Series Generator

| Claim | Verdict | Evidence |
|---|---|---|
| Generates Fibonacci numbers | Supported | The program calculates each next term using `next = a + b`. |
| Generates the Fibonacci series | Supported | The loop generates and prints a sequence of Fibonacci numbers. |
| Uses an iterative approach | Supported | The program uses a `for` loop rather than recursion. |
| Demonstrates loops and variable updates | Supported | The loop updates `a` and `b` during each iteration. |
| Accepts the number of terms from the user | Not Supported | The number of terms is hardcoded as `n = 10`. |

## 4. Student Record Program

| Claim | Verdict | Evidence |
|---|---|---|
| Stores a student's name, roll number, and marks | Supported | The dictionary contains `name`, `roll`, and `marks` keys. |
| Uses a Python dictionary | Supported | The variable `student` is defined as a dictionary. |
| Accesses information using dictionary keys | Supported | The code accesses values using `student["name"]`, `student["roll"]`, and `student["marks"]`. |
| Displays student details | Supported | The program prints the student's name, roll number, and marks. |
| Provides student record management | Not Supported | The program only stores and displays fixed details; it does not implement record management operations. |
| Accepts student information from the user | Not Supported | The student details are hardcoded in the dictionary. |

## 5. Technologies and Requirements

| Claim | Verdict | Evidence |
|---|---|---|
| Uses Python | Supported | All three files contain Python source code. |
| Uses Python dictionaries | Supported | The student record program uses a dictionary.
