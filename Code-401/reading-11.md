# Event Driven Applications

[Event Driven Programming](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)

**What native Node.js module allows us to get started with Event Driven Programming?**

- EventEmitter. We are able to access the EventEmitter class through its events module. To actually implement it in an application, we will need to create a new object from the class to start using it.

```javascript
const EventEmitter = require('events').EventEmitter;
const myEventEmitter = new EventEmitter;
```

**What is the value of Object Oriented Programming used in tandem with Event Driven Programming?**

- "All behavior of an individual object should be handled from code within that unit."

- The two working in tandem make for a valuable, functional, and practical movement amongst parts. 

- By utilizing event driven programming, our objects can just emit the functions attached to our events whenever they occur instead of needing to pull from other objects in the code. It, to me, feels like streamlining the process.

**Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.**

- Events are important because any action that you participate in within your web browser is an action that will fire off the code that will allow you to actually do a thing. What makes event driven programming important is that it synchronizes all of the events that can go into an application to, in turn, make the program as streamlined as possible.

Bookmark & Review

[Documentation: Node Docs - Events](https://nodejs.org/api/events.html)