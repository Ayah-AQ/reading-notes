# Class03: Data Modeling

## Reading

### nosql vs sql

> Q1: What type of database is the best fit for the complex query intensive environment?
>> For databases that need to handle complex queries, SQL databases are the best choice. They are designed to handle complicated questions about data efficiently and provide powerful querying capabilities.


> Q2: What type of database is the best fit for hierarchical data storage?
>> If you have data with a hierarchical structure (like parent-child relationships), NoSQL databases are a good fit. They allow you to store and manage data in a way that reflects these hierarchical relationships more easily.

> Q3: Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
>>  When it comes to scalability, SQL databases scale up by making a single server more powerful, like adding more resources to a computer. NoSQL databases scale out by adding more servers to handle the workload, similar to having multiple computers working together. This allows NoSQL databases to handle large amounts of data and traffic more effectively.

### sql modeling techniques

> Q1: Among data tables, what is a one-to-many relationship and how do we “relate” them?
>> In a one-to-many relationship, one record in a table can have multiple related records in another table. We relate them by using a foreign key, which is a column in the "many" table that refers to the primary key in the "one" table.

> Q2: Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
>>  to create a diagram 

> Q3: Explain the difference between a primary and foreign key.
>> A primary key is a unique identifier for each record in a table, ensuring that each record has a distinct identity. A foreign key is a column in a table that refers to the primary key of another table, establishing a relationship between them. The primary key uniquely identifies records within a table, while the foreign key links records between different tables.

## Videos

### sql vs nosql

> Q1: How do we treat keywords and parameters differently in SQL syntax?
>> In SQL, keywords have reserved meanings and cannot be used as identifiers for tables or columns without special handling. Parameters are values passed into SQL queries to make them dynamic and reusable.

> Q2: Define normalization within the context of schemas and data.
>>  Normalization is the process of organizing a database to eliminate redundancy, improve data integrity, and minimize duplication and anomalies. It involves breaking down large tables, establishing relationships, and optimizing data structure.

> Q3: Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
>> In database relationships, a one-to-one relationship means each record in one table is connected to a unique record in another table. A one-to-many relationship allows one record in a table to have multiple connections with records in another table. A many-to-many relationship means multiple records in one table can be connected to multiple records in another table.

###

```
In the Data Modeling class, the goal is to learn how to create data models in JavaScript. These models describe the properties and behaviors of objects and help solve problems in application development. The class covers CRUD operations, SQL and NoSQL databases, and modeling relational data using Sequelize. It also teaches SQL commands and provides a Collection class for performing database operations. The class aims to give students the skills to work with data and build applications effectively.
```