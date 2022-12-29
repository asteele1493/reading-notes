# Access Control (ACL)

[5 Steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

**What is Role Based Access Control (RBAC) and why do we care?**

- RBAC is a way to assign privileges/access to users in a company based on their role in that organization. It's a management tool designed to streamline access.

**Describe a Role/Permission heirarchy that you might implement using RBAC.**

- The first example that comes to mind is Google Docs. When you create a document, you are the root user. But you are able to assign roles to others depending on what you need. If you're collaborating on a project, you may need to assign editing permissions to others. If you're sharing a document, you may want that user to just be able to view or comment. I could see this type of hierarchy applied to larger scale applications.

**What approach might you take to implement RBAC?**

- The approach laid out in the article makes the most sense to me in terms of actual implementation. 

  - Inventory the resources in question. Whatever you're wanting to expand access to.
  
  - Analyze who will be needing access to them-- is there a hierarchy within your organization or team?

  - Assign people to roles.

  - Stick to said roles. Adjusting them on the fly will lead to discombobulation within the system itself. It is best to reassign roles when the time is come rather than adjusting the roles themselves to fit a person.

  - Review the system periodically to ensure it's working as desired.

[Wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

**If Authentication is “you are who you say you are,” what is Authorization?**

- Authorization says "Great! Let's see what you have permission to look at."

**Name three primary rules defined for RBAC.**

- Role assignment: Where a user can only exercise a permission if that user has been selected for or assigned a role.

- Role authorization: Where the user's role must be authorized.

- Permission authorization: Where a user can exercise a permission only if the permission is authorized for the user's active role.

**Describe RBAC to a non-technical friend.**

- RBAC is a system that you can put in place to ensure the people who need access and certain privileges to resources get them based on their role in an organization, and vice versa for those that don't.

[VIDEO: RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

**What Are access rights Associated with? The User? or The Role? Explain.**

- Access rights are associated with the role, not the user. You assign access rights to a role, that is then assigned to a user. Assigning access rights to a user defeats the purpose of RBAC. Users must be activated into those roles.

**Access Rights, or Authorization, is activated after a user successfully does what?**

- They are activated after a user is successfully authenticated.

**Explain how RBAC might benefit a business.**

- RBAC systems can remain in place after users leave since privileges are not granted to users, rather privileges are granted to roles.
