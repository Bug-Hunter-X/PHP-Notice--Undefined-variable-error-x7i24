# PHP Notice: Undefined variable error

This repository demonstrates a common PHP error: "Undefined variable" notices. These notices occur when you try to use a variable that hasn't been assigned a value.

## The Bug

The `bug.php` file contains a function `myFunction` that may return an undefined variable `$result` if the code within the function doesn't explicitly assign a value to it.  This leads to a PHP Notice, which, while not a fatal error, can indicate a logic flaw in the code and may be undesirable in production environments. 

## The Solution

The `bugSolution.php` file provides a corrected version of `myFunction`, where `$result` is explicitly initialized or a default value is returned in case it is not set within the function's logic. 
