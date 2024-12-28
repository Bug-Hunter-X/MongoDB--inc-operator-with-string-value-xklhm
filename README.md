# MongoDB $inc operator with string value
This example demonstrates an issue related to using the `$inc` operator in MongoDB update operations with a string value instead of a number. This leads to an unexpected result in the database.
The `bug.js` file contains the incorrect code, while the `bugSolution.js` file provides the correct solution using a numerical value for the `$inc` operator.
## Bug
The original code attempted to increment the `counter` field by the string '1', which resulted in an incorrect update. 
## Solution
The corrected code increments the `counter` field by the number 1, resulting in the expected behaviour.