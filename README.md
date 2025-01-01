# MongoDB $inc Operator Bug
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is designed to increment or decrement a numerical field in a document. However, if the field does not exist, the `$inc` operator will not create it. This can lead to unexpected behavior in your application. 

This repository contains two files:

- `bug.js`: This file demonstrates the incorrect usage of the `$inc` operator.
- `bugSolution.js`: This file demonstrates the correct way to handle this scenario.