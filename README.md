# Unclosed Parenthesis in Function Definition
This repository demonstrates a common Python error: an unclosed parenthesis in a function definition.  The error is subtle because the syntax error only occurs when the interpreter attempts to execute the faulty code.  This can be hard to track down since it may not generate an error during the writing process.

## Bug
The `bug.py` file contains a function definition with an unclosed parenthesis. This results in a `SyntaxError` when the interpreter tries to parse the code.

## Solution
The `bugSolution.py` file corrects the error by adding the closing parenthesis. This simple fix allows the code to run without errors.
