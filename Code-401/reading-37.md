# Redux: Combined reducers

[Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

Why create multiple reducers?

- When you want to act on multiple pieces of information. Using multiple reducers allows you to react to actions and return a new state object.

How would you combine multiple reducers?

- If your application had two reducer functions, you would import combineReducers from redux, and use both reducer function names as the arguments.

How will you manage state as an immutable object? why?

- Always return a new state object. You can do this by modifying the reducer function itself to take in the action's payload.

```state = {...state, name: action.payload}```

[Documentation: Using combined reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

- ```combineReducers``` is a utility function to simplify the most common use case when writing Redux reducers.

Explain how ```combineReducers``` assembles the new state tree.

- "```combineReducers``` will call each slice reducer with it's current slice of state and the current action, giving the slice reducer a change to respond and update its slice of state if needed." What I think this means is the ```combineReducers``` function will tap into the slice reducer that corresponds to the slice of state its currently holding. The state its holding will tell the reducer what change to state needs to be done and update accordingly.

How would you define initial state in an app using ```combineReducers```?

- There are two approaches listed in the documentation for defining initial state shape. The first is to include the ```preloadedState``` parameter as the second argument to the ```createStore``` function. The second is to just return the initial state value when the state argument is undefined.

[Documentation: combined reducer syntax](https://redux.js.org/api/combinereducers/)

Why will you want to split your reducing functions as your app becomes more complex?

- You'd want to do this to manage separate, independent parts of state.

The combineReducer helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

What is a popular convention when naming reducers?

- To explicitly specify the names of hte keys in the slice reducer object to define the keys in the output state object. It's not good practice to use words like 'reducer' in the state key names.