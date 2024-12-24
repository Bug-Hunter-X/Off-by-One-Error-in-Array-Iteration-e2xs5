# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error leads to an `ArrayIndexOutOfBoundsException`.

The `bug.java` file contains the erroneous code. The `bugSolution.java` file provides the corrected version.

This is a simple example to illustrate a subtle but frequently encountered programming mistake.

## How to Reproduce

1. Compile and run `bug.java`. Observe the exception.
2. Compile and run `bugSolution.java`. Observe the correct output.

## Lesson Learned

Always carefully consider array indices when iterating.  Remember that arrays are zero-indexed, meaning the valid indices range from 0 to `array.length - 1`.