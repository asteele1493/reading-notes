# JS Debugging

## [Troubleshooting Javascript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

- Name some key differences between a Syntax Error and a Logic Error.
  - These are the two main types of code errors you'll come across. Syntax errors are pretty self explanatory. They are errors thrown when a piece of the code is spelled incorrectly. These types of errors will point to where the issue is, and the error is typically able to be fixed quickly. Logic errors are errors in the code's logic. There usually isn't a point of reference to correct this error as the fault is in the logic... I feel like these are the types of errors I usually get haha. 

- List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
  - A good segway from the last question! The one that stands out the most to me is the logic errors I received upon turning in our About-Me assignment. I had a couple of loops that weren't running correctly and I couldn't figure out why. I had my return inside of my for loop (I think this is how it went) and so my code was either running in an infinite loop, or it just wasn't running at all. This learning experience helped the concept of looping click for me. 
  - Another example that's coming to mind is in our current Salmon Cookies lab. I've had a really hard time wrapping my mind around building tables and rendering content using DOM manipulation. In my head, it makes sense. But when I get to actually building it, I flop pretty quickly. A lot of it is getting my syntax right-- making sure my syntax is written in the correct order, especially when appending elements. Same issue with the tables, but I've been literally drawing them out so I can visualize where my information is going. Rendering is another issue... 

- How will this topic continue to influence your long term goals?
  - I feel like debugging will be a constant part of the programming life cycle. I don't get a lot of the concepts we discuss in class right away. It takes me a good while to solidify something in my head, and honestly it tends to happen a few classes after the initial discussions. But getting errors in the codes I write has been a learning experience in solidifying syntax, as well as a big pointer to gaps in my understanding. 

## [The Javacript Debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)

- How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
  - The JS debugger is a tool used to catch bugs in code. It allows you to select certain sections or pieces of the code you think have issues, and see if they run, or find out why they don't.

- Define what a breakpoint is.
  - A breakpoint is where you want your code to pause while debugging, so that your console will only run the block of code before and up to that breakpoint.

- What is the call stack?
  - The call stack shows you what code was executed to get you to the breakpoint/current line. I'm wondering if these are generally just functions?