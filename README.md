# Incorrect Use of $inc Operator in MongoDB Update

This repository demonstrates a common error in MongoDB update operations: using the `$inc` operator with a non-numeric value.

The `bug.js` file shows the incorrect implementation, attempting to increment a string field using `$inc`. This leads to an error because `$inc` expects a numeric value.

The `bugSolution.js` file provides the corrected code, where the field being incremented is a number.