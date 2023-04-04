# Redux

[Dan Abramov Redux Tutorial](https://egghead.io/courses/getting-started-with-redux)

[Transcription/notes on Abramov course github](https://github.com/tayiorbeii/egghead.io_redux_course_notes)

What is the first principle of Redux?

- The first principle of redux is that the entire state of the application will be represented by one Javascript object.

what is a store and what do we use our reducers for within that store?

- Stores combine the three principles of Redux: it holds the current app state object, allows you to dispactch actions, and when you create it, you need to specify the reducer that tells how state is updated with actions.

Name three Redux store methods given to us by createStore and describe their use.

- Store has three important methods:
  - ```getState()``` which retrieves the current state of the Redux store.
  - ```dispatch()``` which is how we dispatch actions to change the state of the application.
  - ```subscribe()``` which registers a callback that the redux store will call any time an action has been dispatched so you can update the UI of yoru app to reflect the current app state.

Explain to a non-technical recruiter what combineReducers() does and why it is useful.

- There are different states your app will need to account for as they change. ```combineReducers()``` is a way to take all of the reducer functions in our application, combine them into one reducer function, and consolidate the state in our application.

## Bookmark & Review

[World's easiest guide to redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

[Testing Reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Documentation: Redux](https://redux.js.org/)