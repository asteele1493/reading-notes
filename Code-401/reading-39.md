# Redux - Additional Topics

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

What concerns are addressed by Redux Toolkit?

- There are three common concerns users have had about Redux that RDK strives to make easier. Concerns about: 
  - making configuring a redux store easier to do
  - not needing a bunch of packages installed to get Redux to do things
  - eliminating the amount of boilerplate code needed

What does ```configureStore()``` do?

- it wraps ```createStore``` and provides streamlined configuration options/defaults. It does a lot under the hood we don't see such as ```combineReducers``` and thunk by default.

How would I use ```createSlice()```?

- You would pass in any reducer functions, a name for the slice, and any state values you would need to track in your application. It's a 'slice' of an application that you can easily access.

[MobX](https://mobx.js.org/getting-started.html)

What is Mobx?

- A library that helps manage state within an application.

How does MobX make it “impossible” to produce an inconsistent state?

- It ensures that anything and everything can be derived from the application state, and will be derived automatically.
  - It does this by treating your application like a spreadsheet. In addition to state and actions, there are also derivations or any value that can be computed automatically from teh state of your application.
  - In addition to derivations, there are reactions. Reactions make sure the DOM is rendered correctly or check to ensure any network issues don't arise.

How would we build a reactive user interface?

- You would use the observer HoC wrapper from the mob-react-lite package that will wrap the React component in autorun.

[TUTORIAL](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)

##  Bookmark & Review

[Redux Toolkit](https://redux-toolkit.js.org/)

[HookState](https://hookstate.js.org/)