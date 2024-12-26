# CSS Calc() Issue: Undefined Parent Width

This repository demonstrates an uncommon CSS bug related to the `calc()` function and its reliance on the parent element's width.  The bug occurs when the parent element does not have an explicitly defined width, causing unexpected layout results in some browsers.

The `bug.css` file contains the problematic CSS rule. The `bugSolution.css` file provides a solution to address the issue.

This bug highlights the importance of ensuring parent elements have defined widths when using `calc()` for accurate calculations.