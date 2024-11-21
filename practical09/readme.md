# Magic Square Checker

## Overview
This program checks if a given square matrix is a Magic Square. A Magic Square is a square matrix where:
1. The sum of every row, column, and both main diagonals equals the same value `M`.
2. The matrix size is a positive integer `n`.

The program:
1. Reads the matrix from a file.
2. Computes whether the matrix satisfies the conditions of a Magic Square.
3. Outputs the result to the console.

## Files
### 1. **Source Code**
- **`main_stub.c`**: Contains the main program logic for file reading and Magic Square validation.
- **`magic_square_stub.h`**: Header file declaring the `isMagicSquare` function.

### 2. **Input Files**
- **`magicsquare.txt`**: Contains a valid Magic Square matrix.
- **`notmagicsquare.txt`**: Contains a matrix that is not a Magic Square.

**Compile and run the program**:
```bash
gcc main_stub.c -o mainstub -lm
./mainstub
```

### Output
[sp55@sciprog practical09]$ ./mainstub
Enter file name: magic_square.txt
No. lines, 3
M = 15
This is magic!

[sp55@sciprog practical09]$ ./mainstub
Enter file name: not_magic_square.txt
No. lines, 3
M = 15
Row 1 does not sum to 15 (row sum = 6).
This is not magic