## Refactoring
## Rice Cooker Simulator Refactoring Benchmark

## Overview

This repository contains a Rice Cooker Simulator program that has undergone refactoring for improved code readability and maintainability. This document details the complexities of the original code and how they have been addressed in the refactored version.

## Original Code

The original code used a series of nested `if-else` statements to handle user input, leading to potential readability issues and redundant code. The `while` loop structure with multiple conditions made it harder to follow the flow of the program.

### Benchmark Results

The benchmark results for the original implementation are as follows:

- **Number of Conditional Statements:** 11


- **Lines of Code:** 27

Those numbers correspond to the part of the code analysed and refactored, not the whole code.

## Refactored Code

The refactored code uses a `switch` statement to simplify the handling of user input. It also removes unnecessary nested conditions, improving the overall readability of the code.

### Benchmark Results

The benchmark results for the refactored implementation are as follows:

- **Number of Conditional Statements:** 6
   - Fewer conditional statements generally indicate simpler code logic.
  
- **Lines of Code:** 24
  - Fewer lines of code generally indicate more concise and readable code.


## Complexity Analysis

1. **Readability:**
   - Original Code: The nested `if-else` statements made the code less readable.
   - Refactored Code: The use of a `switch` statement improves code readability and reduces redundancy.

2. **Maintainability:**
   - Original Code: Multiple nested conditions make it challenging to maintain and extend the code.
   - Refactored Code: The refactoring simplifies the logic, making it easier to maintain and add new features.

3. **Code Redundancy:**
   - Original Code: Redundant conditions and repeated code for each choice.
   - Refactored Code: Redundancy is reduced, and the code for each choice is more concise.

### Conclusion

## Conclusion

Based on the benchmark results, the refactored implementation **reduced** the number of conditional statements from 11 to 6 and **reduced** the number of lines of code from 27 to 24 compared to the original implementation. The switch statement provides a more structured and readable code, which contributes to better maintainability.

