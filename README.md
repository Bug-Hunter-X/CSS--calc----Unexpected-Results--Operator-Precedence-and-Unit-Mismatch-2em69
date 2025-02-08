# CSS `calc()` Pitfalls
This repository demonstrates common issues encountered when using the `calc()` function in CSS, specifically concerning operator precedence and unit consistency. The `bug.css` file showcases code that produces unexpected results.  The `bugSolution.css` file provides corrected code and explanations.

## Issues:
* **Operator Precedence:**  `calc()` follows standard mathematical operator precedence.  Misunderstandings of this can lead to incorrect calculations.
* **Unit Mismatch:**  Units must be consistent for addition and subtraction.  Mixing percentages, pixels, ems etc. without proper nesting or conversion will cause errors.

## Solutions:
The `bugSolution.css` file demonstrates the proper way to resolve these issues using parentheses for explicit precedence control, and by ensuring consistent units within each operation.