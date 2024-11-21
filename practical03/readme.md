# Trapezoidal Rule Approximation of Logarithmic Function

This C program uses the trapezoidal rule to approximate the value of `log(2)` by integrating the tangent function between two points. It calculates the sum of tangent values over intervals and compares the result with the actual value of `log(2)`.

## Table of Contents
- [Description](#description)
- [Usage](#usage)
- [Compilation](#compilation)
- [Sample Output](#sample-output)
- [Explanation](#explanation)

## Description

The program calculates the trapezoidal sum using tangent values over an interval from `a = 0` to `b = π/3`. It approximates the result and compares it to the actual value of `log(2)`. The absolute and relative differences between the calculated and actual values are printed.

### Key Calculations:
- Sum of the tangent values before the loop.
- Update of the sum within the loop with even-number checks.
- Final sum using the trapezoidal rule formula.
- Comparison with the actual value of `log(2)`.

## Usage

Modify the following parameters if needed:
- `n`: Number of intervals.
- `a` and `b`: The integration limits.

### Steps:
1. Compile the program.
2. Run the program to see the trapezoidal sum and its comparison with `log(2)`.

## Compilation

To compile the program, use the following command:

```bash
gcc trap.c -o trap -lm
```
Here, -lm is used to link the math library for the tan() and logf() functions.

Run the program:
```bash
.\trap
```
### Sample Output

The value of sum before loop is: 0.577350
I'm even and here's the value of sum 0.557334
The value of sum after loop is: 0.557334
The final value of sum is: 0.029839
The actual value of sum is: 0.693147
abs_diff = 0.663309
rel_diff = 0.956944

### Explanation
The program computes the following:

1. a is the lower limit of the interval.
2. b is the upper limit (π/3).
3. The trapezoidal sum approximates the integral of the tangent function, which is compared to the actual value of log(2).
Absolute Difference (abs_diff): The difference between the calculated and actual value.

Relative Difference (rel_diff): The relative error in the calculation.
