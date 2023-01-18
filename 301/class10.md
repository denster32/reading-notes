# Class 10 Notes - In Memory Storage

## Summary of Topics

### Understanding the JS call stack

1. What is a ‘call’?

- a call is when a function is invoked
- the call stack refers to all of the calls waiting to be executed at any given time
2.How many ‘calls’ can happen at once?
- the call stack is synchronous therefore only one call can happen at a time

3. What does LIFO mean?

- last in, first out

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

-   a ------    fn a() => fn b() => fn c() => fn d()
    | 1     |
    b ------
    | 2     |
    c ------
    | 3     |
    d ------
    | 4     |
      ------

5. What causes a Stack Overflow?

- stack overflow occurs when there is a recursive function, a function that calls itself, without an exit point. similar to an infinite loop.

### JS error messages

1. What is a ‘reference error’?

- occurs when something is wrong with a variables reference in your code

2. What is a ‘syntax error’?

- occurs when an app executes a script with syntax errors that the linting tool did not catch

3. What is a ‘range error’?

- thrown when a variable is set with a value outside of its legal values range

4. What is a ‘type error’?

- created when some value does not turn out to be of a particular expected type

5. What is a breakpoint?

- its a line that you select where the code pauses so that you can see what happen there, also known as stepping through code

6. What does the word ‘debugger’ do in your code?

- most popular way to debug is to run console.log() so that you can see if your code is outputting what you want/need it to
