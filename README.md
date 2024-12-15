# Missing 'end' Keyword in Lua 'if' Statement

This repository demonstrates a common error in Lua: forgetting to close an `if` statement with the `end` keyword.  The code in `bug.lua` will result in a syntax error because the `if` statement is not properly terminated.

The solution (`bugSolution.lua`) shows the corrected code with the `end` keyword added. This simple oversight can lead to confusing errors, especially in larger functions or nested conditional statements.

**How to Reproduce:**
1. Run `bug.lua` using a Lua interpreter.
2. Observe the syntax error.
3. Run `bugSolution.lua` to see the corrected code.