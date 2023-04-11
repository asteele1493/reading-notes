# Redux & Asynchronous Actions

[Async Actions](https://redux.js.org/advanced/asyncactions)

**Why use Redux middleware?**

- Redux reducers do not contain any side effects nor can you intentionally put side effects in reducers, but utilizing Redux middleware allows us to create those side effects throughout our applciation while allowing asynchronous logic to interact with our Redux stores and dispatches.

**Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.**

- The data flow begins with an action and how we handle it-- when we dispatch, the action is sent to the middlware
- The middleware triggeres the asynchronous logic hich then gets sent back through the middleware and dispensed to our reducers within our store
- The object gets changed in state and sent through to our UI

**How are we accommodating async in our Redux app?**

- By using redux-thunk. After installing, we'd just update our Redux store to use that middleware.

[Thunk Middleware](https://github.com/reduxjs/redux-thunk)

**Why would you need redux-thunk middleware?**

- Because using just Redux does not allow for asynchronous logic. Middleware expands your application's functionality.

**Redux Thunk middleware allows you to write action creators that return a function instead of an action.**

**Describe how any return value from the inner thunk function will be made available.**

- The return value from a thunk function is available as the return of the original dispatch. Thunk action creators dispatch each other and return Promises.
