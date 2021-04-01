# THE CALL STACK :

The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

**Manage function invocation (call):** The call stack maintains a record of the position of each stack frame. It knows the next function to be executed (and will remove it after execution). This is what makes code execution in JavaScript synchronous.
## How does the call stack handle function calls?


1. When `secondFunction()` gets executed, an empty stack frame is created. It is the main (anonymous) entry point of the program.
2. `secondFunction()` then calls firstFunction()which is pushed into the stack.
3. `firstFunction()` returns and prints “Hello from firstFunction” to the console.
4. `firstFunction()` is pop off the stack.
5. The execution order then move to `secondFunction()`.
6. `secondFunction()` returns and print “The end from secondFunction” to the console.
7. `secondFunction()` is pop off the stack, clearing the memory.

## stack overflow:

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

# JavaScript error messages && debugging :

**Reference errors**
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.
the fact that this happens to let and const is called Temporal Dead Zone (TDZ).

**Syntax errors**
I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

**Range errors**
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

**Type errors**
this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

The fix is simple, just make sure that method exists before trying to access it, either by creating method or by checking for undefined.

## Debugging:

To debug your JS code, the easiest and maybe the most common way its to simply `console.log()` the variables you want to check or, by using chrome developer tools, open your page with your JS code *(press cmd+o in macOS or Ctrl+o in Windows)* and choose your file to debug, click the line you wanna debug and refresh your page again (F5).
The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.
You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. In this example the breakpoint will point stop when the index reaches 40.
