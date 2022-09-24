# Passing functions as props

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

**What does .map() return?**

- `.map()` is very similar to `forEach()`, but it actually returns something. It creates an array with populated results. Some caveats to this though, is that you cannot call the `.map()` method on strings or integers, only arrays.

**If I want to loop through an array and display each value in JSX, how do I do that in React?**

- You'd use curly braces! Anytime you want to use jsx in a JS file, use curly braces. When you want to exit jsx, you'd use parens to get back into javascript.

**Each list item needs a unique ____.**

- ID. I think, even if you have duplicate values, assigning an ID to each item is important. We did this in our JSON files.

**What is the purpose of a key?**

- Akey is an attribute you can give to a string when you're creating a list of elements. They help React figure out what items have been modified in any way. You can assign keys to unique list ID's.

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

**What is the spread operator?**

- The spread operator is a way to expand an iterable object array into the list of arguments. They syntax is composed of ellipses `(...)`. 

**List 4 things that the spread operator can do.**

- Among others, the spread operator can use an array as arguments, combine objects, add to state in React, and copy an array.

**Give an example of using the spread operator to combine two array**

**note: examples are taken from the reading**

``` javascript
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

**Give an example of using the spread operator to add a new item to an array.**

``` javascript
const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
```


**Give an example of using the spread operator to combine two objects into one.**

``` javascript
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
```

[How to Pass Functions between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

**In the video, what is the first step that the developer does to pass functions between components?**

- They create the function they want the state to change. 

**In your own words, what does the increment function do?**

- The increment function loops through the people array, utilizing the `.map()` method and updates the state of each person's count with each iteration. It adjusts the state.

**How can you pass a method from a parent component into a child component?**

- You'd pass the method just as you would props. example: `increment={this.increment}`

**How does the child component invoke a method that was passed to it from a parent component?**

- You'd pass the method just as you would props. example: `increment={this.increment}`

## Things I want to know more about

- Still not completely understanding why keys are important. I understand what they do, but why wouldn't I just use the ID to pull information?

- Just a note, I really liked the youtube video for the readings. This dude explains things very well. Will definitely be revisiting his channel.

### To Bookmark & Review

[React tutorial, 'Declaring a Winner'](https://reactjs.org/tutorial/tutorial.html)
[React docs, Lifting State up](https://reactjs.org/docs/lifting-state-up.html)
