# React and Forms

[React documentation on Forms](https://reactjs.org/docs/forms.html)

**What is a ‘Controlled Component’?**

- A controlled component is where we take mutable state (where we can only update with setState) and elements that maintain their own state (where it gets updated by user input) have a baby! This would, in turn, make it so that what is held in React (the react state) is the one and only truth. In other words, the input's value is always driven by the React state.

**Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

- I believe we should update the state with the user's input as soon as it's entered. I'm still not sure how this works in it's entirety, but if a component is controlled, the user's input will update with each new keystroke.

**How do we target what the user is entering if we have an event handler on an input field?**

- I think you would add an attribute to each possible element, that way depending on what the user ends up doing, the handler function will be triggered in any situation.

[Conditional Ternary Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

**Why would we use a ternary operator?**

- You'd use a ternary to simplify if statements. I do really like the logic behind the syntax. I think this is a ternary's purpose? Simplification.

**Rewrite the following statement using a ternary statement:**
```javascript
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

``` javascript
(x==y) ? true : false
```

## Things I want to know more about

- Honestly feeling a little nervous about controlled components. Feels like there's going to be lots of moving parts and event handlers.

### To bookmark and review

[React Bootstrap & Forms](https://react-bootstrap.github.io/forms/overview/)

[React Documentation on Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)