# JavaScript Bug: Handling Null and Undefined

This repository demonstrates a common but subtle bug in JavaScript related to handling `null` and `undefined` values.  The `foo` function aims to return the length of an input, or 0 if the input is null. However, it exhibits unexpected behavior under certain conditions.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version that addresses the identified issue.

## Bug Description:

The original code attempts to handle `null` inputs correctly but fails to explicitly handle `undefined` inputs.  This leads to an error when an undefined value is passed to the function.

## Solution:

The solution uses strict equality (`===`) and checks explicitly for both `null` and `undefined` to ensure robust handling of various input types.
