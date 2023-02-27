# Component Based UI

[React Hello World](https://facebook.github.io/react/docs/hello-world.html)

[Supplemental reading on Elements vs. Components](https://www.geeksforgeeks.org/what-is-the-difference-between-element-and-component/)

[Supplemental reading on React design principles](https://reactjs.org/docs/design-principles.html)

**What are the building blocks of a React app?**

- Components are the parts that make up a React app.

**What is the difference between an element and a React component?**

- Elements are object representations of nodes. Elements are returned by components. Where an element is immutable, meaning it cannot be changed, components' state is mutable. Components also encapsulte DOM trees. In my head, I imagine components being made up of elements.

**What are some advantages of React’s component based architecture?**

- React's component based architecture allows for expanded functionality without needing to change an entire codebase.

- Allows for flexibility in the application, especially when the pre-existing components have well-defined functionality.

- 'ility': React's component based architecture is scalable, extensible, replaceable... it encomposses lots of non-functional requirements that make it accessible and desirable.

[Intro to JSX](https://facebook.github.io/react/docs/introducing-jsx.html)

**What is JSX and why do we use it?**

- JSX is a syntax extension to Javascript. It also produces React elements.

**Describe the process of embedding JavaScript expressions in JSX.**

- You would declare a variable

- And then when using the variable inside of JSX, wrap it in curly braces

- After wrapping your JSX in curly braces, you can insert it in any regular Javascript expression.

**Is it safe to embed user input in JSX? Explain.**

- Yes, React DOM escapes any value embedded in JSX before rendering them. Everything is converted to a string beforehand.

**Further notes**

- React doesn't separate technologies, rather it separates concers by using components. 

- JSX tags can have children

[Rendering Elements](https://facebook.github.io/react/docs/rendering-elements.html)

[On state and mutability](https://reactjs.org/docs/state-and-lifecycle.html)

**Explain what a React Component is to a non-technical friend.**

- Components are building blocks in React. They are comprised of smaller pieces that do a thing and are based on a single responsibility. When building our or refactoring a project, you can plug and play with the components you already have. 

**Describe mutability and React Components, specifically, how is the UI updated?**

- Mutability refers to a component being able to change during the duration of a program.

**If changes are made to the UI, what does React update?**

- React will only update the DOM node whose contents have changed.

**Notes**

- React components are like functions in Javascript. The easiest way to define a component is to write a JS function:

```javascript

function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

```

- Props are read only, pure. They cannot or do not ever attempt to change their inputs, and always return the same results for the same inputs.

- All React components must act like pure functions with respect to their props.

## Bookmark & Review

[Airbnb React/JSX Style Guide](https://airbnb.io/javascript/react/)

[SASS Cheatsheet](https://devhints.io/sass)

[React Cheatsheet](https://devhints.io/react)

[Another React Cheatsheet](https://reactcheatsheet.com/)
