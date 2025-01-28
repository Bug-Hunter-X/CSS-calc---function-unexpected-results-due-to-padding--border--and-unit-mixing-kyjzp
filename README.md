# CSS Calc() Function Unexpected Behavior

This repository demonstrates a common issue encountered when using the CSS `calc()` function: unexpected results when dealing with padding, borders, and unit mixing.  The `bug.css` file showcases the problem, while `bugSolution.css` provides the corrected CSS.

## Problem
The `calc()` function in CSS is powerful but requires careful handling.  Incorrect unit usage or neglecting padding/border effects can lead to layout inconsistencies.

## Solution
The solution involves understanding that `calc()` operates on the content box.  Consider the total size of the parent element (including padding/border) or adjust the calculation accordingly.  Also, ensure consistent unit usage within the `calc()` expression to avoid errors.