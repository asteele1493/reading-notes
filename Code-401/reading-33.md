# ```<Login /> & <Auth/>```

[What is role-based access control(RBAC)?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

What is Role Based Access Control (RBAC)?

- Role Based Access Control is a way to limit accessability by role. Essentially, who has access to what.

- Align roles and access permissions based on an employee's position in an organization.

Share some an example of RBAC including all possible CRUD operations and correlating roles.

- Add and remove members as they leave and join your company.
  - Add and remove members within a designated role.

- End user may only be able to read certain parts of an application.

- Technical members may only be able to perform specific, technical tasks; some of which may require sensitive data.

- Billing members may need to update sensitive payment information.

What are the Benefits of RBAC?

- RBAC ensures that sensitive data is accessibly only to the people that need it.

- Reduces administrative work and IT support; there are less password changes and documentation that need to get done.

- Gives you control over what users can and can't do in a streamlined approach.

[react-cookie library](https://www.npmjs.com/package/react-cookie)

[react-cookies component](https://www.npmjs.com/package/react-cookies)

Describe some react-cookie features.

- The ```useCookies([])``` syntax is similar to the syntax we have been using, with a dependency array.

- Similar to useState, we can establish a cookie name, and set the cookie's value.

- Give access to cookies anywhere in the application by adding specific props to the component.

- get, getAll, and set methods.

- You wrap your ```<App>``` in a ```<CookiesProvider>```.

Describe some react-cookies features.

- ```npm i react-cookies --save```

- Looks like it doesn't use hooks?

- will need to import cookie into app, and require in component.

Which library would you prefer would you prefer? Why?

- I'm still getting the hang of hooks-- where to use them/why you'd use them/etc., but the documentation for the first react-cookie introduction made more sense to me. Seems like it would be easier to implement-- streamlined, less code to write, and would follow the syntax of what we've been learning this module.
