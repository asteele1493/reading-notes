# AWS: API, Dynamo & Lambda

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

**What is Amazon API Gateway?**

- Amazon API Gateway is a service that manages HTTPS requests to your API endpoints and correctly routes them to the correct backends. Amazon API Gateway is also able to mesh with other Amazon services allowing for fully managed authentication and authorization layers. The GUI associated with the service also aids in sketching out API structure.

- API Gateway is also a way to create RESTful API's and WebSocket API's that enable real-time, two-way communication applications.

**Why is Amazon API Gateway an important part of the Serverless ecosystem?**

- API Gateway marries Serverless functions to API definitions. Using the service brings the same pros to using AWS as the previous services we've talked about-- it's just as scalable, efficient, accessible, etc.

**How does API Gateway integrate with other AWS services?**

- The example mentioned that is directly related to previous labs/readings is how API Gateway interacts with Lambda and how it's able to run Labda functions to generate HTTP API responses.

- API Gateway is also able to make an HTTP call against the API of any AWS service that provides an HTTP API.

- Can return a mock response generated within the API Gateway without calling out to other services.

[AWS API Gateway](https://aws.amazon.com/api-gateway/)

**What are the some benefits of using Amazon API Gateway?**

- As mentioned in the previous reading, API Gateway is very '-ible'. It's scalable, accessible, flexible, secure, and efficient-- among other things.

- One of the things I'd like to know more about is it's monitoring feature. Getting data metrics on an API sounds cool. Wondering how much of that coincides with CloudWatch.

**What two API types might you choose from?**

- RESTful API's || WebSocket API's

[AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

**What is DynamoDB?**

- DynamoDB is a NoSQL database hosted on AWS.

**Under what circumstances would you recommend DynamoDB over MongoDB?**

- I suppose I would recommend DynamoDB if you were working with other AWS services. Sounds like a natural fit.

- I could see an application that foresees scaling wanting to use DynamoDB over MongoDB-- scaling and security would be two points I'd prioritize if I chose Dynamo.

[AWS DynamoDB](https://aws.amazon.com/dynamodb/)

**Explain to a non-technical friend how DynamoDB works.**

- The workings of Dynamo seems pretty straightforward to me at first glance. At it's core, you would want to use the service to configure your database and it's key features-- capacity, security, tables, etc. 

- Once your database is set up, you could export it and integrate with other AWS services/monitor data metrics after deployment.

[Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

**What is Dynamoose?**

- Dynamoose is a modeling tool for DynamoDB, similar to Mongoose.

**What are some key features of Dynamoose?**

- The key features listed in the documentation are as follows:

  - Type safety
  - High level API
  - Easy to use syntax (similar to that of Mongoose)
  - DynamoDB Single table design support
  - Ability to transform data before saving/retrieving items
  - Strict data modeling
  - Support for DynamoDB transactions
  - Powerful conditional/filtering support
  - Callback and promise support
  - AWS Multi-region support
