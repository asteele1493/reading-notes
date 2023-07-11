# API Integration

[Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

- Explain the different between a query string parameter and a path parameter.

  - A query string parameter is part of the path parameter. A path parameter is a part of a URL that takes you to an endpoint, and gives you the result of a query. 

- What would our API URL with a path id parameter be given the following information:

1. Domain: http://our-site.com
2. v3
3. model name: stuff
4. id: things

```http://our-site.com/v3/stuff/things```

- We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

  - It's 5 o'clock and we are at a restaurant ordering food. Our server writes down our order to take to the kitchen to begin preparing our food. The interface in this instance would be the notepad-- it's a thing that allows the server to communicate with the kitchen to access and acquire food items for you and your dining partners. An interface is something you can interact with to acquire data.

[Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

- Describe how you would use middleware to implement basic and bearer auth.

  - For basic auth, we would need to have the ```Basic (username + password)``` correct and have it lead to the ```/signin``` route only.

  - For bearer auth, we would need to have access to the bearer token generated by our request to authenticate successfully. 

- Describe the handshake necessary to implement OAuth.

  - OAuth authentication happens by a third party. Once our request is sent using the correct oauth route, our middleware will validate the user and return an object with a re-authentication/bearer token and the user object OR an error.

- Describe how Role Based Access Control works to a non-technical friend.

  - RBAC is a way to streamline access to resources. Users will have predetermined capabilities that they can interact with the application with. If there is an editor of a newspaper, they will have the ability to do more than just read the newspaper-- they should also be able to update and delete articles. If I'm just a subscriber, I would only be able to read since that is as far as my access goes.