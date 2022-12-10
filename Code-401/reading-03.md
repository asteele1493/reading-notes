# Express REST & API

[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

**Classes are a template for creating ____.**

- Objects!

**Can a class declaration be hoisted?**

- No, they cannot. Function declarations on the other hand can be.

**How would you describe a constructor and contextual “this” to a non-technical friend?**

- A constructor is a way to streamline creating objects that have something in common. When we say 'this', we're talking about the object being described.

[Using Express Routing](https://expressjs.com/en/guide/routing.html)

**Within Express, what does routing refer to?**

- Routing refers to how an app's endpoints respond to user requests.

**What is the difference between a route path and a route method?**

- A route path helps define an endpoint, whereas the method defines how we'll get there.

**When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?**

- It's appropriate to add next when we want to continue on with arguments to the next callback function. In my head, using next just keeps the ball rolling.

[Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

**What is an Express Router?**

- An express router is similar to a mini application. It provides us with methods to link paths to each other.

**By what mean do we initialize express.Router() in an express server?**

- I think I understand this question-- by initializing with express.Router(), we're saying there are specific methods we want to use within it. This can include basic routes, API routes, and even authentication routes.

**What do we use route middleware for?**

- "Route middleware is a way to do something before a request is processed." I've previously heard middleware defined as 'software glue'. It's software that helps us do things that aren't necessarily related to requests within the application. I think.
