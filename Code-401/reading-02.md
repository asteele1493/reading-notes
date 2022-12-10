# Express, NPM, TDD, CI/CD

[An Introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

**Explain middleware, answer as though I were a non-technical recruiter.**

- Middlware can be thought of as "software glue". Middlware is software that can help with essentially any operation within an application regardless of os.

**Express the most popular __ __ ____.**

- Express is the most popular Node web framework.

**Express is “unopinionated.” What does that mean?**

- Being unopinionated in this sense refers to not having as many restrictions to achieve a goal. There is no "right" way to do something, in fact, there are probably many ways.

**What is a module and why is modularity useful to us as developers?**

- A module is a library or file that you can import and use in code. Modules are useful because they help developers ascribe to the single responsibility principle. Pulling in solid, widely used modules can help make developing applications easier by offloading the work into something already established.

[What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

**What version of npm are you running on your machine?**

- 8.19.3

**What command would you type to install a library/package called ‘jshint’ into your node project?**

- ```npm i jshint```

- npm is the world's largest software registry.

[What is TDD?](https://www.agilealliance.org/glossary/tdd/)

- TDD stands for test-driven development.

**Explain why tests are important. Please explain as though I were your non technical elder.**

- Tests are important in software engineering because they help refine and expose any bugs in the code. They also help in ensuring new features are working okay before they get put into production.

**What are three expected benefits of testing?**

- less errors are made

- pushing a project through it's final stages becomes easier because the time spent testing the code saved time.

- testing inherently creates better code. It improves the team internally.

**Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.**

- writing tests that are too long

- forgetting to run tests often

[On CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

**What are three benefits of Continuous Integration?**

- You get feedback faster by having builds and tests.

- Fixes to code can be deployed faster.

- Adjusts the failure rate and defects of code.

**What is the difference between Continuos Delivery and Continuous Deployment?**

- Continuous delivery lets you develop features in a modular, manageable way, able to release at any time. Continuous deployment is an extension of continuous delivery; allows to deploy new features with little if any downtime.

**Explain how GitHub fits into this process assuming the listener comes from a non-technical background**

- CI/CD in the most simplest terms refers to automation. Making our lives easier in regards to developing software. Github offers us tools that make this process easier like version control, 'builds' or mock ups of files that are accompanied by checks, and the ability to review modifications and code quality.

[Supplement: On CI/CD](https://resources.github.com/ci-cd/)

## To Bookmark & Review

[Documentation: NodeJS](https://nodejs.org/en/docs/)

[Documentation: NPM](https://docs.npmjs.com/)

[Documentation: Express](https://expressjs.com/en/4x/api.html)

[HTTP Status Codes](https://www.restapitutorial.com/httpstatuscodes.html)

[Supertest](https://github.com/visionmedia/supertest)
