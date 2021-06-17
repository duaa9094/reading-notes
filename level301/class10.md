## Understanding the JavaScript Call Stack

1. What is a ‘call’?

function invocation 

2. How many ‘calls’ can happen at once?

one at a time

3. What does LIFO mean?

Last In, First Out, means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

4. What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.


## JavaScript error messages

1. What is a ‘refrence error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

This is also a common thing when using const and let, they are hoisted like var and function but there is a time between the hoisting and being declared .

2. What is a ‘syntax error’?

occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3. What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

An array for instance cannot have a negative length.

4. What is a ‘tyep error’?

This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5. What is a breakpoint?

At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code

6. What does the word ‘debugger’ do in your code?

Stops the execution of JavaScript, and calls (if available) the debugging function. 