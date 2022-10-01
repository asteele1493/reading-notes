# Putting it all together

[React Documentation- Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

**What is the single responsibility principle and how does it apply to components?**

- The single responsibility principle is the idea that components should be able to do one thing and one thing only. Although React is known for being able to scale widely and do so successfully, this does not exclude the fact that sometimes established components must be deconstructed into sub components to adhere to this single responsibility principle.

**What does it mean to build a ‘static’ version of your application?**

- Building a static version of your app requires you to build out the UI/UX of the design. It will render some of the data you have, but will not link the rendered product with any interactivity.

**Once you have a static application, what do you need to add?**

- You'll need to add the changes your app will experience. The triggers that will need to go off in order for the user to see moving parts and inputs/outputs. Youll need to add state. 

**What are the three questions you can ask to determine if something is state?**

- Is it passed in from a parent via props? If so, it probably isn't state.

- Does it remain unchanged over time? If so, it probably isn't state.

- Can you compute it based on any other state or props in your component? If so, it isn't state.

**How can you identify where state needs to live?**

- Find a common owner component-- a component the other components that will utilize state have in common, and pass it down. If you can't fine one, create a state component solely for holding state and add it into the hierarchy.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

**What is a “higher-order function”?**

- They are functions that operate on or take in other functions as arguments.

**Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?**

- Line two is saying to return any number that is greater than the number originally taken in. 

**Explain how either `map` or `reduce` operates, with regards to higher-order functions.**

- The map method applies a function to each element value in a given array and modifies them to return a new array. Same length, but different content.

## Things I'd like to know more about

- Not a question, just a comment. Really enjoyed the Thinking in React article. Very helpful in tying concepts togheter for me.
