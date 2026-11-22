[README.md](https://github.com/user-attachments/files/35230150/README.md)
# LCA Assignments

This repository contains C programming assignments and lab exercises for the LCA course.

**Author:** Ansh | **Language:** C | **Compiler:** Terminal (Ubuntu)

---

## Index of Programs

1. **Largest of Three Numbers**
   - **File:** `Assignment 2`
   - **Description:** Takes three integers as input and prints the largest of them using `if / else if / else` and logical operators.

2. **Menu-Driven Calculator**
   - **File:** `Assignment 3`
   - **Description:** Takes two numbers and repeatedly shows a menu to add, subtract, multiply, divide or exit, using a `while` loop and `switch-case`.

3. **Matrix Addition**
   - **File:** `Assignment 4`
   - **Description:** Reads two matrices of the same size, displays them and prints their sum using 2D arrays and nested loops.

4. **String Operations Menu**
   - **File:** `Assignment 5`
   - **Description:** Menu-driven program to concatenate, find the length of, copy and compare strings using `string.h`.

5. **Factorial**
   - **File:** `Assignment 6`
   - **Description:** Finds the factorial of a number in two ways: using recursion and using a loop.

6. **Student Record System**
   - **File:** `Assignment 7`
   - **Description:** Stores roll number, name and marks of 3 subjects for `n` students using an array of structures, and calculates total and percentage.

7. **Swap Two Numbers (Pointers)**
   - **File:** `Assignment 8 (Pointer 1)`
   - **Description:** Swaps two numbers using a function that receives their addresses (call by reference).

8. **File Copy**
   - **File:** `Assignment 8 (Pointer 2)`
   - **Description:** Copies the contents of one file into another character by character using `fopen`, `fgetc`, `fputc` and `fclose`, with error checking.

---

## Concepts Covered

- Decision making and menus (`if-else`, `switch-case`)
- Loops (`for`, `while`, `do-while`)
- Arrays and 2D arrays
- Strings and `string.h` functions
- Functions and recursion
- Structures
- Pointers
- File handling

---

## How to Run

Open a terminal in the repository folder and compile with GCC. The files have no `.c` extension, so tell GCC they are C code with `-x c`:

```bash
gcc -x c "Assignment 2" -o assignment2
./assignment2
```

Replace `Assignment 2` with the file you want to run. If you rename the files to end in `.c`, you can leave out `-x c`.

---

## Conclusion

Together these programs take you from simple logic to organising data and working with memory and files. Each assignment builds on the previous one and gives a solid base for writing larger C programs.
