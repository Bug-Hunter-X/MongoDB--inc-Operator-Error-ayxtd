# MongoDB $inc Operator Error

This repository demonstrates an uncommon error that occurs when using the `$inc` operator in MongoDB. The error happens when a string value is provided to the `$inc` operator instead of a number, leading to unexpected update results.

## Bug
The `bug.js` file shows incorrect usage where '1' (a string) is passed instead of 1 (a number). This results in the `field` not being incremented correctly.

## Solution
The `bugSolution.js` file demonstrates the correct way to use `$inc` by providing a numerical value for incrementing the `field`. 
