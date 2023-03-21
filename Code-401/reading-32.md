# Context API - Behaviors

[Scaling up with Reducer and Context](https://react.dev/learn/scaling-up-with-reducer-and-context)

How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)

- useReducer reduces the amount of event listeners in your application that pertain to updating the app's state.

- You'll need a way to pass useReducer down via props to allow other components access. You can pass it down as props, but when you run into numerous components, deeply nesting your useReducer function will become increasingly confusing and harder to tease out.

- In this case, you would couple the useReducer function with Context.

To do this:

  - Create the context
  - Put state and dispatch into context
  - Use context anywhere in the tree

- This ensures that state still remains at the top level of the application, but is accessibly to every component below it.