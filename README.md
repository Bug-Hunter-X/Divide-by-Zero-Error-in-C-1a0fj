# Divide-by-Zero Error in C

This repository demonstrates a common error in C programming: division by zero. The `bug.c` file contains the erroneous code, while `bugSolution.c` provides a corrected version.

The bug is caused by attempting to divide the integer variable 'a' by the integer variable 'b', where 'b' is 0.  This leads to undefined behavior and a program crash or unpredictable results.

The solution involves adding a check to ensure that the denominator is not zero before performing the division.