## Dynamic Memory Allocation and Factorial-Based Approximation of e
This repository contains two separate C programs that demonstrate dynamic memory allocation, factorial computation, and basic pointer usage in C.

### Program 1: **Factorial-Based Approximation of e**

### Overview
This program calculates an approximation of the mathematical constant \( e \) using a series expansion:
\[
e \approx 1 + \frac{1}{1!} + \frac{1}{2!} + \frac{1}{3!} + \cdots
\]

The user inputs the order of the series (number of terms to compute), and the program calculates and displays the approximation of \( e \).


### How to Run
Compile and run the program using GCC:
   ```bash
   gcc e.c -o e -lm
   ./e
   ```

### Output
Enter the order of the series: 14
5! is 120
1.0000000000000000
0.5000000000000000
0.1666666666666667
0.0416666666666667
0.0083333333333333
0.0013888888888889
0.0001984126984127
0.0000248015873016
0.0000027557319224
0.0000002755731922
0.0000000250521084
0.0000000020876757
0.0000000005175840
0.0000000007818943
e is 2.71828182958565

### Program 2: **Dynamic Memory Allocation and Array Manipulation**

### Overview
This program demonstrates the use of dynamic memory allocation and pointers in C. It includes the following functions:

1.Allocate memory dynamically for an integer array.
2.Fill the array with 1 using a pointer.
3.Print the contents of the array.
4.Free the allocated memory.

### How to Run
Compile and run the program using GCC:
   ```bash
   gcc pointer.c -o p -lm
   ./p
   ```
### Output
1 1 1 1 1

