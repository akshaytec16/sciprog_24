## Matrix Multiplication in C

This repository contains a simple program to perform matrix multiplication in C. The program calculates the product of two matrices \( C \) such that \( C_{n \times q} = A_{n \times p} \times B_{p \times q} \). The implementation includes separate files for the main program, matrix multiplication logic, and a header file, along with a Makefile for easy compilation.


### Modular design with separate files for clarity:
- **`main.c`**: Main driver program.
- **`mathmult.c`**: Contains the logic for matrix multiplication.
- **`mathmult.h`**: Header file for function declarations.
- **`Makefile`**: For compilation and building the project.

### How to Run:
- Using Makefile
```bash
make
```
- Without using Makefile
```bash
gcc -o matrix_multiply main.c mathmult.c
```
- Then run the executable
```bash
./matrix_multiply
```

### Output:

**Matrix \( C \):**
5.00 2.00 -1.00 -4.00 8.00 2.00 -4.00 -10.00 11.00 2.00 -7.00 -16.00 14.00 2.00 -10.00 -22.00 17.00 2.00 -13.00 -28.00
