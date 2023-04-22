# Progressive Web Apps

[What are PWA's](https://web.dev/what-are-pwas/)

**What does Progressive in Progressive Web App mean?**

- Progressive refers to the enhancement to web apps that you see with the three pillars of PWA's experience.

  - In the dictionary, progressive oftentimes refers to a gradual progression, step-by-step OR advocating for new ideas, a reforming of some sort. I'd say in this context, PWA could refer to this "new" type of app, a new idea.

**What are three benefits of writing a progressive web app, as opposed to a native app?**

- The three pillars are that its capable, reliable, and installable. Non functional requirements.

**What are two reasons to consider a native app, instead of a PWA?**

- I'm not entirely sure why, but think it may have something to do with capability and having a dependable, reliable connection. 

[App manifests](https://web.dev/add-manifest/)

**When a website has an app manifest, what is it able to do?**

- It's able to tell whatever browser the user is using more about the PWA and how it should behave when installed. It has properties relating to the description, name, images, URL.

**Name and describe how short_name and two other manifest properties are used.**

- ```short_name``` seems like a topic of sorts. What it the overall theme of this application.
- ```icons``` are image objects that the user will see on load, different screens, etc.
- ```start_url``` is required and it's the home path of where your app will start.

**How does Chrome render a PWA splash screen?**

- Chrome will initially include the name, background_color, and icons in the splash screen before spinning up the application.
