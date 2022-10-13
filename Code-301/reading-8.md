# APIs

[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

**What does REST stand for?**

- REST stands for Representational State Transfer. 

**REST APIs are designed around a ____.**

- They are designed around a resource. A resource can be any kind of object, data, or service that can be accessed by a client.

**What is an identifier of a resource? Give an example.**

- This is a URI which will identify a resource uniquely. A URI is a uniform resource identifier. I believe this can take shape as a unique URL.

**What are the most common HTTP verbs?**

- GET, POST, PUT, PATCH, and DELETE.

**What should the URIs be based on?**

- URI's should be based on nouns. Preferably, nouns that directly relate to the resource.

**Give an example of a good URI.**

- `./orders` vs. `./create-order`

- My understanding is that our HTTP method is already using verbs and active language. Our URI should be based on the object, not what it's doing. Maybe an adjective?

**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

- Having a chatty API means an application has a lot of resources it wants/tries to grab. This can result in long wait times and not getting what the client actually needs.

**What status code does a successful GET request return?**

- 200

**What status code does an unsuccessful GET request return?**

- 400

**What status code does a successful POST request return?**

- 202

**What status code does a successful DELETE request return?**

- 204

## To Bookmark and Review

[RexExr](https://regexr.com/)

[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

[Regex 101](https://regex101.com/)

[A Podcast I found that I rly enjoyed listening to](https://apiacademy.co/2017/02/what-exactly-is-rest/)

- I spend most of my work days driving, and so I in turn listen to lots of programming podcasts. I found this one to be particularly cool.
