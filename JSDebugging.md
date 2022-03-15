# Error Handling & Debugging  
---  
When writing code you will ultimately end up making mistakes, here are some ways to help you *debug* your code.  

Knowing the order of execution will help immensley when writing code. Your code runs from the top of the screen to the bottom. This is known as the **Stack**.  

Knowing the difference between your execution context is also important.  
- Global context. Code that is in the script but not inside of a function.  
- Function context. Code that is being run within a function.  

Each time a script enters a new execution context, there are two phases.  

1. Prepare. 

The new scope is created, variables, funtions, and arguments are created.  

2. Execute.

Values are assigned to variables. Reference functions and run their code. Execute statements.  

## Error Objects  

Error objects can and will help you find where your mistake is located. These can be found in your console. They are as follows.  

- Error: Generic error, all other errors are based upon this object.  
- SyntaxError: Syntax has not been followed.  
- ReferenceError: Tried to reference a variable that is not declared/within scope.  
- TypeError: An unexpected data type that cannot be coerced.  
- RangeError: Numbers not in an acceptable range.  
- URIError: encodeURI(), decodeURI() and similar methods used incorrectly.  
- EvalError: eval() function not used correctly.  

If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Which is a variation of an *if* conditional.  
