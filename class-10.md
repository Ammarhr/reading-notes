## Java Error Handling & Debugging:
Every long **Javascript**  code,there are nobody gets the right code for everything at the first time. so the **Errors** are something expected in any code. the browser helps the web developer to determines what went wronge in the javascript.

### ORDER OF EXECUTION:
**Javascript**  excute the code in order. so ther are functions couldn't work before other functions.

### EXECUTION CONTEXT:
There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope:
- **GLOBAL CONTEXT**: Code that is in the script, but not in a function.

- **UNCTION CONTEXT**: Code that is being run within a function. Each function create its own function context.

- **VARIABLE SCOPE**: The first two execution contexts correspond with the notion of scope .

---------------------
### Stack:
the javas interpreter procecesses one line of code at a time. when a statement needs data from another function, it stacks or piles the new function on top of the current task

### Debugging Errors:
**Debugging Errors:** is the process of finding errors. It involves a process of deduction.
 
>>**The console** helps narrow down the area in which the error is located, so you can try to find the exact error.

### types of errors:
1. RangeError This is thrown when a number is outside an allowable range of values.
2. ReferenceError This error is thrown when a reference made to a variable/item is broken. That is the variable/item doesn’t exist.
3. SyntaxError This is the most common error we encounter. This error occurs when we type code that the JS engine can understand.
4. TypeError TypeError is used to indicate an unsuccessful operation when none of the other NativeError objects are an appropriate indication of the failure cause.
5. URIError This indicates that one of the global URI handling functions was used in a way that is incompatible with its definition.
6. EvalError This is used to identify errors when using the global eval() function.
7. InternalError This error occurs internally in the JS engine, especially when it has too much data to handle and the stack grows way over its critical limit.