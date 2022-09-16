# Introduction to React and Components

## [Component Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

- **What is a component?**

  - A component is a block of code (or unit of composition) that encapsulates well-defined functionality. It's a software object that can interact with other components to expand on its own functionality.

- **What are the characteristics of a component?**
  
  - *Reusability*: Although some components are designed for use one time, most components are intended to be reusable.

  - *Replaceable*: Echoing the previous characteristic, components can be freely exchanged and swapped out with other components that are similar in composition.

  - *Not context specific*: They are designed to operate in different environments and contexts. Universal?

  - *Extensible*: Components can be extended from its original purpose; it can be added to to increase its functionality.

  - *Encapsulated*: The components are what happens under the hood; they are encapsulated. When used well, the user will not be able to see the inner-workings, only the user interface.

  - *Independent*: They are designed to have minimal dependencies and can operate independantly.

- **What are the advantages of using component-based architecture?**

  - You are able to reduce the time in development cost by reusing existing components. Same applies to the actual usage of the application-- your project is more reliable because you are able to use existing, working components.
  
## [What is Props and How to Use it in React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)

- **What is 'props' short for?**

  - 'Props' stands for 'properties'. In React, data flows in one direction (from parent to child).

- **How are props used in React?**

  - Props are used to transfer data from one component to another.
  
  *Data should not be changed by child elements.*

  -**Steps to using props**

  - Define an attribute and it's value

  - Pass it to the child component

  - Render the data

- **What is the flow of props?**

  - One directional? As in the data flows in one way, from parent to child?

## Things I want to know more about

- Honestly, my mind is kind of blown with being introduced to componenents, and I'm just stoked to learn more.

### To Bookmark and Review

- [Tutorial: 'Passing data through props'](https://reactjs.org/tutorial/tutorial.html)

- [Documentation: Hello World](https://reactjs.org/docs/hello-world.html)_

- [Documentation: Introducting JSX](https://reactjs.org/docs/introducing-jsx.html)

- [Documentation: Rendering Elements](https://reactjs.org/docs/rendering-elements.html)

- [Documentation: Components and Props](https://reactjs.org/docs/components-and-props.html)
