# From the Duckett JS book:
## JavaScript book, Ch. 10, “Error Handling & Debugging”

Order of Execution

- Execution of Contexts
    - Global
    - Function
    - Eval

Variables have scope

> The Stack: the JavaScript interpreter processes one line of code at a time.  When a statement needs data from another function, it stacks the new function on top of the current task.

### Execution Context & Hoisting
There are 2 phases of activity, preparation and execution.  Hoisting is functions and variables can be called or referenced before they are declared

**OBJECT**           **DESCRIPTION**
Error                Generic error - the other errors are all based upon this error
SyntaxError          Syntax has not been followed
ReferenceError       Tried to reference a variable that is not declared/within scope
TypeError            An unexpected data type that cannot be coerced
RangeError           Numbers not in acceptable range
URIError             encodeURI ().decodeURI(),and similar methods used incorrectly
EvalError            eval() function used incorrectly

The statements `try`, `catch`, `throw`, and `finally` are for error handling and can help gracefully handle errors.

> Debugging is about deduction: eliminating potential causes of an error.

Where is the problem
What exactly is the problem


 







