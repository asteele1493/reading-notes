# Data Modeling

[NoSQL vs. SQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

**What type of database is the best fit for the complex query intensive environment?**

- SQL databases are better suited for complex query intensive environments

**What type of database is the best fit for hierarchical data storage?**

- NoSQL databases work better for hierarchical data storage due to its implicit methods for storing data. This storage is similar to JSON data and is stored in key value pairs.

**Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.**

- SQL databases are able to scale vertically. This means you are able to increase the data load by simply adding more RAM or CPU power to your existing machine. NoSQL databases are better suited for horizontal scaling (i.e. scaling outwards). This means it can manage higher traffic flows with adding more machines to its pool of resources.

[Supplemental reading on scalability](https://stackoverflow.com/questions/11707879/difference-between-scaling-horizontally-and-vertically-for-databases)

[SQL modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

**Among data tables, what is a one-to-many relationship and how do we “relate” them?**

- In reference to databases, a one to many relationship defines the relationship between one "entry" and how that entry can relate to other entries in different tables.

**Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**

- Create a diagram!

**Explain the difference between a primary and foreign key.**

- Primary keys uniquely identify each row in a table whereas a foreign key is a value in a column or set of solumns that match a primary key in another table.

[VIDEO: SQL vs. NoSQL](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

**Define normalization within the context of schemas and data.**

- Database normalization is the process of formally organizing a database according to "normal forms". Normalizing data helps with reducing redundancy in the tables.

**Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**

- A one-to-one relationship is like having a driver's license-- that relationship is unique to you, and there is only one. One-to-many can be likened to the cards in your wallet. They all have a relationship, only to you, but you are able to possess many at once. Many to many relationships can be like students and classes. Students can apply for more than one class, and classes can hold many students. Apologies, I tried to keep the analogy going.

