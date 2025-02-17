# JavaScript Null Value Handling Bug

This repository demonstrates a potential bug in a JavaScript function related to the handling of null values.  The original function attempts to handle cases where either 'a' or 'b' is null, returning 0 in those situations. However, it does not explicitly cover the scenario where both 'a' and 'b' are null simultaneously.  This omission may lead to unexpected outcomes or errors in certain applications.

The `bug.js` file contains the buggy code, while `bugSolution.js` shows a corrected version with improved null handling.

## Bug Description
The main issue lies in the lack of a comprehensive check for the case when both input parameters are null. This can result in an incorrect computation or an unexpected error if the function is called with two null values.

## Solution
The corrected code includes an explicit check for both 'a' and 'b' being null, ensuring that the function behaves as expected regardless of the input values.