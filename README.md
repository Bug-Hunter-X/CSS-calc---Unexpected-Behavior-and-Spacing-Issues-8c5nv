# CSS calc() Issues

This repository demonstrates a common issue encountered when using the `calc()` function in CSS.  Specifically, the examples show unexpected behavior when combining percentages and pixels in `calc()` expressions, and the impact of incorrect spacing.

The `bug.css` file contains the problematic code, and `bugSolution.css` offers a corrected version.

## Problem:
- Inconsistent results when using `calc()` with percentage and pixel values.
- Errors due to incorrect spacing within `calc()` expressions.

## Solution:
- Ensure proper spacing around operators in `calc()` expressions. 
- Double-check the context (parent element's dimensions) when dealing with percentages to avoid unexpected results.