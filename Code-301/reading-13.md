# More CRUD

[CRUD Basics](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)

**Which HTTP method would you use to update a record through an API?**

- You'd use `PUT` as the method. The `PUT` method replaces targeted content with the new, updated content.

**Which REST methods require an ID parameter?**

- `DELETE` and `PUT` both require id parameters as both methods require specific endpoints to target the appropriate document.

[Speed coding: Building a CRUD API](https://www.youtube.com/watch?v=EzNcBhSv1Wo)

**What’s the relationship between REST and CRUD?**

- CRUD is a way to manipulate information, whereas REST is a way to shape information (through HTTP methods).

**If you had to describe the process of creating a RESTful API in 5 steps, what would they be?**

- Creating CRUD routes

- **this would include exporting router, defining routes, and adding in requires**

- Mount my router

- Hook up my database

  - **promises to return data**

  - **define schema**

- Go through CRUD operations and hook up accordingly (i.e. try catches, specify id if needed, etc.)

- Test! This would be an as you go type of situation, but I think deserves it's own bullet point.

## Supplemental reading I found helpful

[REST vs. CRUD](https://www.logicmonitor.com/blog/rest-vs-crud#:~:text=In%20its%20base%20form%2C%20CRUD,not%20limited%20to%20CRUD%20functions.)