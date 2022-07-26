# Class 05 notes on DOM & Javascript objects

## **Javascript object basics**

1. How would you describe an object to a non-technical friend you grew up with?

- I would say something along the lines of an object is a mix of different Javascript data types that are somehow related or can function with each other in some way. A block of code that has data and that you can do something with.

*Object literal* - An object literal sounds like something that contains key value pairs? 

2. What are some advantages to creating object literals?

- Object literals make the transferral of detailed data easier. An object literal can contain lots of information (I'm thinking like a dictionary?)
  and being able to use a unique keyword in transferring that data makes the process less redundant and simpler.

*Dot notation* - The object name acts as the namespace. You need to enter the namespace before you are able to access any other information. Anything after the dot can be
a property you want access to. Can also use bracket notation. 

3. How do objects differ from arrays?

- You are able to differentiate severl items by name instead of by array? I think objects sound more detailed..?

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

- The article mentions when an object property name is defined at runtime, then you can't use dot notation to access the value. You can pass the name as a variable inside brackets.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

- This is a reserved key word in JavaScript. It is used to distinguish between individual objects... I think.

## Introduction to the DOM

1. What is the DOM?

- DOM stands for Document Object Model! It represents the structure of a web page. A programming interface. A web page can be either source HTML or in your browser. DOM allows the page
  to be manipulated regardless of source.The DOM is an API.

2. Briefly describe the relationship between the DOM and JavaScript.

- You can use Javascript to manipulate web pages *using* the DOM. The DOM is independent of any language. To me, it sounds like an API you can call with JavaScript and use to code?

### Things I want to know more about

- Is dot or bracket notation better practice? "Dot is more preferred."
- More examples that detail needing to use bracket notation over dot notation
- I've heard a lot about Node.JS. I'm still unsure about what Node is exactly, but I think it's a way to code in a browser using JavaScript. 
    Would this be DOM utilization?
