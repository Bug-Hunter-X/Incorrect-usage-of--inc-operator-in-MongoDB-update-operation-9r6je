# Incorrect Usage of $inc Operator in MongoDB Update Operation
This repository demonstrates a common error in using MongoDB's $inc operator for updating documents.  The $inc operator requires a numeric value to increment a field.  Using a string will lead to an error.

## Bug
The provided code snippet shows an incorrect application of the $inc operator.  It attempts to increment the 'age' field by '1' (a string), leading to an error.

## Solution
The solution demonstrates the correct usage of the $inc operator with a numerical value to increment the 'age' field correctly.