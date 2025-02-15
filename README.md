# MongoDB $inc operator type error
This example demonstrates an uncommon error in MongoDB when using the $inc operator.  The error arises from providing a string value instead of a numeric value for the increment.

The `bug.js` file shows incorrect usage. The `bugSolution.js` shows the correct way to use the operator.

This can be hard to spot as it doesn't always result in an immediate error, potentially leading to subtle bugs in data manipulation.