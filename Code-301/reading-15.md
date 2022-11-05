# Authentication

[What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

**What is OAuth?**

- It is an authorization protocal or framework that allows for unrelated servers and services to access resources without sharing logon credentials. A third-party, delegated authorization.

**Give an example of what using OAuth would look like.**

- Off the top of my head would be trying to connect a bank to a financial service like Rocket to track expenses. You would need to validate credentials through a third party, like Plaid, before the two are connected.

**How does OAuth work? What are the steps that it takes to authenticate the user?**

- First, the website a user is already logged into will connect to the second site, providing the user's verified identity.

- Then, the second site will generate a one-time token unique to the interaction.

- The first site gives this token and unique code to the user's client.

- The client's software presents the request stoken and secret to their authorization provider.

- The client may need to authenticate the authorization provider.

- The user will then approve the transaction type.

- They are then given an access token.

- Then, the user gives the approved token to the first site.

- The site gives the token to the second site.

- The second site grants access.

- User will see a success message.

**What is OpenID?**

- OpenID is primarily about authentication. It's for humans logging into machines, OAuth is for machines logging in to machines for humans.

[Authorization and Authentication flows](https://auth0.com/docs/flows)

**What is the difference between authorization and authentication?**

- Authorization determines the access rights of a user, while authentication verifies a user's identity.

**What is Authorization Code Flow?**

- Authorization code flow is where the exchange of a token occurs with an authorization code since the code for most web apps aren't public facing.

**What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**

- This is a flow exchange that occurs with mobile devices. When using a mobile device, extra security measures are taken.

**What is Implicit Flow with Form Post?**

- Implicit flow with form post is primarily used for public clients, or applications that can't securely store Client Secrets. Not used often-- but is particularly useful if the app needs just an ID token to perform user authentication.

**What is Client Credentials Flow?**

- This is where the system will authorize the app rather athan a user. Instead of username and login, M2M's use the client credentials flow.

**What is Device Authorization Flow?**

- Another way to authenticate if the device being used cannot input data well. Will redirect user to external link to authenticate.

**What is Resource Owner Password Flow?**

- Where a user name and password are requested. Not recommended though as should only be used when redirect-based flows cannot be used.

## Bookmark & Review

[AuthO for single page apps](https://auth0.com/docs/libraries/auth0-react)

### Supplemental readings I found helpful

[Authentication vs. Authorization](https://www.onelogin.com/learn/authentication-vs-authorization#:~:text=Authentication%20verifies%20the%20identity%20of,the%20security%20of%20a%20system.)
