# Authentication

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

**Explain to a non-technical friend how you would safely hash and store a password.**

- Hashing is a way to store a password by converting it into data that can't be reverted back to it's original form. To do this, you'd want to use a hasing algorithm to convert your original password.

[Supplemental reading: Auth0](https://auth0.com/blog/hashing-passwords-one-way-road-to-security/)

**What is Bcrypt?**

- Bcrypt is a type of hasing function based on (I don't really know exactly what this means) the Blowfish symmetric block cipher cryptographic algorithm.

**Why might you use something like Bcrypt?**

- Ultimately, to make brute force attacks harder to do.

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

**What is Basic Authentication?**

- At it's core, basic authorization is the act of an HTTP user providing a user name and password to make a request.

**What properties are necessary in the header of a Basic Auth request?**

- The header takes in credentials, which are essentially the ID and password are provided.

**How are username:password in Basic Auth encoded?**

- Base64

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

**Define the authentication process to a non-technical recruiter.**

- Authentication when talking about web applications refers to a user providing their credentials (such as a user name and password) to access resources. The user name and password itself will sometimes carry requirements such as character length, special character inclusion, and general strength. Once verified, the user will have access to the application, and if not, the user will be notified of an incorrect input.

**How should your error messaging respond (both HTTP and HTML)? Why?**

- The error message should respond in a generic manner. This is because we want to prevent the creation of a discrepancy factor. The discrepancy factor is where an error message could allow an attacker to determine if the user name is valid or not. They can lead to exposure in terms of password or user name inputs.

**Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.**

## Bookmark & Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)