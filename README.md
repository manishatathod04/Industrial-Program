# C Programming – Function and Assertion Testing

## About This Repository
This repository contains C programs created to practice functions, header files, user input validation, and assertion-based testing.

The main objective is to understand how functions can be declared, implemented, reused, and tested in C programming.

## Files Description

### 1. program14.c – Main Program
- Accepts two integer inputs from the user.
- Uses `scanf()` to read the inputs.
- Checks whether the inputs are valid.
- Uses the `Addition()` function declared in `Header.h`.

### 2. Program15.c – Addition Function
- Contains the implementation of the `Addition()` function.
- Accepts two integer arguments.
- Adds the two numbers and returns the result.
- Demonstrates function implementation and code reusability.

### 3. Header.h – Header File
- Includes the required standard header files.
- Contains the function declaration `int Addition(int, int);`.
- Allows the `Addition()` function to be declared separately from its implementation.

### 4. Program16.c – Assertion Testing
- Uses the `assert.h` header file to test the `Addition()` function.
- Checks the results of adding positive and negative integers.
- Uses assertions to compare actual results with expected results.
- If all assertions pass, the program finishes without displaying an assertion error.

## Concepts Covered
- Functions in C
- Function declaration and definition
- Header files
- User input using `scanf()`
- Input validation
- Return values
- Assertion-based testing using `assert()`
- Code organization and reusability

## Technologies Used
- Programming Language: C
- Compiler: GCC
- IDE: Visual Studio Code
- Version Control: Git
- Repository Hosting: GitHub

## How to Compile and Run

### Run the Main Program
Compile the main program along with the addition function:

```bash
gcc program14.c Program15.c -o MainProgram
