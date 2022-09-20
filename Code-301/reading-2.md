# State & Props

[React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

- Based off of the diagram, 'render' occurs first. 'componentDidMount' occurs as the final step in mounting, in the 'commit phase'.

**What is the very first thing to happen in the lifecycle of React?**

- I think this is mounting? Mounting is where a component instance is created and inserted into the DOM.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**

- Constructor, render, componentDidMount, React Updates, componentWillUnmount

**What does componentDidMount do?**

- componentDidMount is a method that is invoiked after a component is mounted. In my head, I think of componentDidMount as a success message after rendering a component (maybe that's incorrect haha). The article mentioned being wary of calling setState() as the method inherently causes a rerender which could lead to loss of efficiency in the site.

[React State VS. Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

- There are two main ways to pass in data in react: props and state

**What types of things can you pass in the props?**

- You can think of props as arguments to a function. They are what you want to initialze your component to. If you want to display title and subtitle, you can store these 'arguments' in the props to display correctly.

**What is the big difference between props and state?**

- State is something inside of a component. Props you pass into a component while state is handled inside of the component. Props is external, state is internal, in relation to components.
- You can also update state inside of the component. When you change the state in a component, it will rerender that section of your application. 

**When do we re-render our application?**

- State is there for when we need to update any changes to a prop (I think). EX. using a counter application where we increase the count. The state changes with the increase, and the page will rerender based on that update.

- If you want to change something within your application, store it in state.

**What are some examples of things that we could store in state?**

- Input of forms, counter applications...


## Things I want to know more about

### To bookmark & review

[State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
[Handling Events](https://reactjs.org/docs/handling-events.html)
[React tutorial & devTools](https://reactjs.org/tutorial/tutorial.html)
[React Bootstrap documentation](https://react-bootstrap.github.io/)
[Bootstrap cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
[Bootstrap shuffle](https://bootstrapshuffle.com/classes)
[Netlify](https://www.netlify.com/)
