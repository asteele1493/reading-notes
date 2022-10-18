# In memory storage 

[Understanding the Javascript call stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

**What is a ‘call’?**

- A call is pretty much a function invocation (i.e. "Calling a function"). Calls are done one at a time from top to bottom. 

**How many ‘calls’ can happen at once?**

- One. Calls are done one by one, from top to bottom.

**What does LIFO mean?**

- LIFO means last in first out. It means that the last function that gets pushed into the stack is the first to be popped out when the function returns.

**Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**

[Call Stack Error](./images/call-stack-error.png)

- If I were using the example in the article (as listed above), I would invoke the first function, followed by the second, and then the third.

**What causes a Stack Overflow?**

- A stack overflow is what happens when there's a recursive function and no exit point. I got a lot of these errors in 201, but my browser would throw an error at one function over and over again.

[Javascript Error Messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

**What is a ‘reference error’?**

- Pretty straightforward, but it's when your browser can't find what you're referring to like a variable for instance.

**What is a ‘syntax error’?**

- Syntax error can refer to a misspelling or jumbling of syntax. 

**What is a ‘range error’?**

- A range error occurs when you try and manipulate an object and give it an incorrect length.

**What is a ‘type error’?**

- A type error is when your data type is off in some way. Say if you're trying to define something that is undefined.

**What is a breakpoint?**

- A breakpoint is a place in a code editor or console where you can debug. The breakpoint is a line of code you can place a marker on and determine what happens to the code if it is run up until that point in the debugger.

**What does the word ‘debugger’ do in your code?**

- I think the word debugger acts as a hard coded breakpoint-- you'll be able to see what has happened to the code up until that point.

## To Bookmark and Review

[Javascript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)