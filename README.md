# MongoDB $inc Operator Error with String Value

This repository demonstrates an uncommon error related to the MongoDB `$inc` operator. The error occurs when a string value is passed to the `$inc` operator, causing a data type mismatch.  The correct approach is to use a numeric value with `$inc`.  Refer to `bugSolution.js` for the corrected code.