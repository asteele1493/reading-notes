# CRUD

[Status Codes based on REST methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

**In your own words, describe what each group of status code represents:**

- 100’s = These codes give you more information about the context of the error.

- 200’s = These codes are about success. They validate the information being sent or received.

- 300’s = This status dictates any type of redirection that has occurred aka the information requested is elsewhere.

- 400’s = These codes are client errors. Meaning, there isn't anything wrong with the code, just with user input.

- 500’s = This status is in regards to server errors. They can be temporary or permanent.

**What is a status code 202?**

- Status code 202 means that the request has been accepted or is valid. Most commonly used with asynchronous processing.

**What is a status code 308?**

- A redirection code, a 308 will tell you that the route used is no longer available. Aka the URL has changed.

**What code would you use if an update didn’t return data to a client?**

- This would be a 204 code.

**What code would you use if a resource used to exist but no longer does?**

- This would be a 401 code. Meaning, we know the resource had existed at some point, but it no longer does and is inaccessible.

**What is the ‘Forbidden’ status code?**

- This code means the resources requested cannot be accessed because the permisisons are not validated.

[VIDEO: Build a REST API with Node.js, Express & Mongo](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**

- Side note: I really like this Youtuber. Anyway, we need to pull our string out of our server and put it in our .env because it's an environment variable. Once we deploy it, it will not be at localhost anymore.

**What is middleware?**

- Middleware is code that runs when the server gets a request, and before it gets sent to the route.

**What does ```app.use(express.json())``` do?**

- This allows our app to accept json as a response.

**What does the /:id mean in a route?**

- The colon before id means that we want id to be a parameter.

**What is the difference between PUT and PATCH?**

- PUT would update all of the information and PATCH is a partial update. I think.

**How do you make a default value in a schema?**

- You would add in a property to whatever javascript object you want to require, and name it 'require'. It should be a boolean data type with the 'require' key set to a true value.

**What does a 500 error status code mean?**

- This is a server error. In basic terms, it means that something has gone wrong with your server.

**What is the difference between a status 200 and a status 201?**

- A 200 code means the request was received, whereas a status 201 means the request has been successful/accepted.