# MongoDB $inc operator error with string value

This repository demonstrates an uncommon error in MongoDB when using the `$inc` operator with an incorrect data type. The `$inc` operator is used to increment a numerical field in a document.  Attempting to increment a field with a non-numeric value results in an error.

The `bug.js` file shows the incorrect usage, and `bugSolution.js` provides the correct solution.

## How to reproduce

1.  Ensure you have a MongoDB instance running.
2.  Create a collection named `myCollection` with at least one document containing a numerical field named `count`.
3.  Run `bug.js`.  You should observe an error.
4.  Run `bugSolution.js` to see the corrected implementation.