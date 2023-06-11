# Reading-Modeling

## NoSQL vs SQL

**Question-1**: What type of database is the best fit for the complex query intensive environment?

**Answer**: SQL databases.

**Question-2**: What type of database is the best fit for hierarchical data storage?

**Answer**: NoSQL databases.

**Question-3**: Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.

**Answer**: SQL databases scale vertically by increasing hardware resources, while NoSQL databases scale horizontally by distributing data across multiple servers.

## SQL Modeling Techniques

**Question-1**: Among data tables, what is a one-to-many relationship and how do we "relate" them?

**Answer**: A one-to-many relationship is when a record in one table is associated with multiple records in another table. We "relate" them by using **foreign keys**.

**Question-2**: Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

**Answer**: create **a** schema

**Question-3**: Explain the difference between a primary and foreign key.

**Answer**: A primary key is a unique identifier for each record in a table, while a foreign key is a field in a table that refers to the primary key in another table.

## SQL Syntax and Normalization

**Question-1**: How do we treat keywords and parameters differently in SQL syntax?

**Answer**: Keywords are reserved words in SQL with specific meanings, while parameters are values passed to SQL statements to customize behavior or filter data.

**Question**: Define normalization within the context of schemas and data.

**Answer**: Normalization is the process of organizing data in a database to minimize redundancy and dependency, ensuring data integrity and optimizing storage.

## Relationships to a Non-Technical Recruiter

**Question-1**: Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

**Answer**: 
- One-to-one relationship: Each person has only one corresponding entry, like a unique ID number for each employee.
- One-to-many relationship: One person has multiple corresponding entries, like a boss having several subordinates.
- Many-to-many relationship: Multiple people have multiple corresponding entries, like students enrolling in multiple courses and courses having multiple students.

## Reflection

**Question-1** :What are your learning goals after reading and reviewing the class README?

**Answer** : I aim to enhance my understanding of data modeling, which will enable me to effectively work with and manipulate data in JavaScript applications.

 ### return to [Main Read Me File](./README.md)