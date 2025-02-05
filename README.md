# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB updates. The `$inc` operator is used to increment a numerical field by a specified value.  However, the value provided must be a number.  Providing a string leads to an error.

## Bug
The original code attempts to increment the 'field' using a string value ('1').

## Solution
The solution corrects this by providing a numerical value to `$inc`.  This resolves the error and updates the document correctly.