# Advanced State with Reducers

[useReducer Hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

**Name an alternative to the useState Hook.**

- An alternative to the useState hook is useReducer. It's preferable in that it works very well for complex state logic that involves multiple sub-values, or when the next state depends on the previous one. The syntax for useReducer is: 

```javascript
const [state, dispatch] = useReducer(reducer, initialArg, init);
```

- It returns the current state as well as a dispatch method. I didn't really know what that meant, but Redux articles talk about dispatching actions as similar to triggering an event in the application.

[Redux docs on dispatch](https://redux.js.org/tutorials/fundamentals/part-2-concepts-data-flow)

**What are two ways to set the initial state?**

- The simplest way is to pass the initial state as a second argument in the reducer hook. I think this would be the initialArg in the syntactical example above?

- The other way to set initial state is to pass an init function as a third argument. The initial state will be set to ```init(initialArg)```

[Ultimate guide to useReducer](https://blog.logrocket.com/guide-to-react-usereducer-hook/)

**In terms of state, what does useReducer expect to receive as a parameter?**

- The first parameter it expects is a reducer function. The second parameter it expects is the initial state.

**What does useReducer return?**

- The hook returns an array that holds the current state value and a dispatch function you're able to pass an action/event to, and to later invoke.

**Explain dispatch to a non-technical recruiter.**

- Dispatching an event is something that can only be sent to the reducer only. Dispatch is a fancy way of saying triggering an event. In this instance, you're able to determine when you want the dispatch to go off. I think.
