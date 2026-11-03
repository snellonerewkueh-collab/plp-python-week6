
# Week 6 Assignment - Safe Functions

This repository contains my Week 6 Python assignment on handling errors using safe functions.

## Files

- `safe_tools.py` - Contains three Python functions: safe_divide(), safe_number(), and get_field(), using try and except to handle errors safely.
- `README.md` - Provides the assignment description, file explanations, and answers the question about input validation.

## Question: Why can the if check not catch abc on its own?

An if check alone cannot reliably handle every possible invalid input during number conversion. When Python tries to convert "abc" into an integer using int(), it raises a ValueError. Using try and except allows the program to catch this error and return a friendly message instead of crashing.

## Expected Output

```text
5.0
Cannot divide by zero
42
Not a number
82
Field not found
```

## Author

Python Software Engineering Student - Week 6
