# useState() Hook

[Introducting Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

**What was the motivation for introducing Hooks?**

- To solve some of the challenges users experienced using React. Some of these challenges included:

  - Having a tough time reusing state between components 
  - Needing to tease out dense, hard to understand components that have grown, and being able to break them up into smaller functions.
  - Understanding that the entry point to learning React can be difficult if you don't already know some fundamental Javascript syntax and it's meaning.

**What changes are important regarding implementing Hooks versus Component Classes?**

- Kind of building off of the challenges listed above, some of the way hooks are implemented/made their way into React change the way we use the language in that: 
  - Hooks allow us to reuse state without changing component hierarchy.
  - Within components, you can split the logic into smaller functions rather than splitting up the component based on life cycle.

**Hooks allow you to reuse stateful logic without changing ___ _______.**

- Component hierarchy

[Hooks API](https://reactjs.org/docs/hooks-overview.html)

**Name two rules imposed by React Hook usage.**

- You can only use hooks at the top level; not inside loops, conditions, or nested functions. Can't do hooks conditionally.
- You can only cll hooks from React function components, not from regular Javascript functions

**How would you identify a custom Hook and why might you create one?**

- It would start with 'use' in the name, and it'd call other hooks -- that is what React identifies as a custom hook.

[The State Hook](https://reactjs.org/docs/hooks-state.html)

**What is a Hook?**

- They are a new React feature that allows you to use state and other features without using a class. It lets you 'hook into' features in React.

**When would I use the useState Hook?**

- When you want to add React state to function components.

**If you were to add React state to a function component by declaring a state variable:**

  - What does calling useState do?

    - It declares a state variable within our application.

  - What do we pass to useState as an argument?

    - The only argument in useState() is the initial state, which does not have to be an object.

  - What does useState return?

    - useState returns a pari of values - the current state and a function that updates it.

## Bookmark & Review

[Hooks API Reference](https://reactjs.org/docs/hooks-reference.html)