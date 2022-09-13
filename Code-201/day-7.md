# HTML Tables, JS Constructor Functions

## [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

- Explain why we need domain modeling.

- Domain modeling is the act of creating a conceptual model to solve a specific problem. It denotes all of the building blocks, constraints, and behaviors that can be associated with a specific problem domain.

- To define the same properties among many functions, you should use a constructor function.

- "After the constructor function definition, two objects are instantiated with the `new` keyword and their properties are initialized by calling the constructor function name.

*Steps to creating a new object in Javascript*

- The new keyword instantiates an object
- The constructor function initializes properties inside that object using the 'this' variable.
- The object is stored in a variable for later use.


## [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

- Tables are rows and columns that hold data.

- Why should tables not be used for page layouts?
  - Tables aren't the right tool for page layouts. They aren't accessible in terms of cohesive web page design, and they'll be harder to maintain once used.
- List and describe 3 different semantic HTML elements used in an HTML <table>.
  ```<td>``` represents table data.
  ```<tr>``` represents table row.
  *You can create a row of data using ```<td>``` flanked by ```<tr>``` tags.
  ```<th>``` represents table header.

## [Intro to Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

- What is a constructor and what are some advantages to using it?
  - A constructor is when you need to create more than one object at a time. An object literal is when you want to create only one object at a time (I think). A constructor is a function that utilizes the ```new``` key word to initialize.
- How does the term this differ when used in an object literal versus when used in a constructor?
  - I think they differ in that the word *this* in an object literal refers to the object name. In a constructor, it refers to a group of objects?
