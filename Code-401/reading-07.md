# Bearer Authorization

[Introduction to JWT](https://jwt.io/introduction/)

**What is a JSON Web Token (JWT)?**

- A JSON web token is a standard that provides a definition for how JSON objects transmitted amongst parties need to be contained and compacted in order to ensure security.

**When should we use JSON Web Tokens?**

- The two main examples given in the article are in reference to Authorization and Information Exchange. Using JWTs during authorization is most common. Every request made from the user's side will request a JWT to access routes and resources.

- In regards to Information exchange, the article mentions how signed JWTs make for secure exchange.

**Claims are expected in which structural component of a JWT?**

- The payload contains the claims. Claimes are statments about an entity and any additional data needed.

[Are JWTs Secure](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

**If I get a JWT and I can decode the payload, how can we call that secure?**

- Regardless of being able to decode the payload, if the JWT is encrypted, you won't be able to change it's contents without knowing the private key.

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**

- The payload and secret?

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**

- In the signature of the JWT, you'd want to include the payload and secret. Only the sender and recipient should know the secret. Regardless of if the content changed, if the user doesn't have that secret, the JWT remains secure.

[VIDEO: JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

**Why use JWT?**

- It's a secure way to transport data. The data sent and received is verified and trusted and unaltered once sent. It's also open standard meaning it's accessible to everyone. JWTs are also compact and can be sent, quickly, via http requests or in http headers.

**JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**

- In short, JWTs being compact and self-contained just means you can send data quickly and without needing to add a bunch of structure to it.

**What are the three components (the structure) of a JWT signature?**

- There are three parts: the header, the payload, and the signature.

- The header is a JSON object that includes an algorithm and the type.

- The payload is also a JSON object and contains the claims attached to the JWT. It is base-64 encoded as well.

- The signature ensures that the data will not change. The header is essentially the concatenation of the base-64 header, base-64 payload, and a secret. This will ensure any changes to the data will not go through if the secrets do not match.

## Bookmark & Review

[DOCUMENTATION: NPM jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)