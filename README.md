# Uncommon CSS `calc()` Errors

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS, particularly within flexbox layouts.  The `bug.css` file contains the problematic code, and `bugSolution.css` shows the corrected versions.

**Issue:** Incorrect usage of `calc()` can lead to unexpected layout shifts and rendering problems. The issues highlighted include problems with unit usage and missing spaces between operators and values in `calc()` expressions.

**Solution:**  The solution involves careful consideration of units within `calc()` and ensuring correct spacing between operators and values.

**How to reproduce:** Clone this repository and open `bug.html` in a web browser. Observe the unexpected layout. Then, replace `bug.css` with `bugSolution.css` and see the corrected layout.  This demonstrates the impact of the `calc()` errors and their solutions. 