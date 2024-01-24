# Databases

**[A database][datacamp1] is a storage system to house your structured data**. It can be a:

- File-based database: It is a single file on your local machine, with the extension name `.db`, `.sqlite`, etc. You can open this file with database viewer to see its structure.
- Directory-based database: Other database systems use directories to store their data. Inside these directories, you will find multiple files that make up the database.
- Server-Based database: Some databases are managed by a database server, and the actual data files may be stored in a location defined by the server.

## Advantage of using databases

TODO: kdnuggets

## Types of databases

### Relational database structure

[A relational database][aws] stores information in tabular form, with rows and columns representing different data attributes and the various **relationships between the data values**.

![](./assets/relational-databases.svg)

### NoSQL databases

TODO: kdnuggets

---

# FAQ

### I usually use pickle to save my data in Python, why would I bother about using databases instead?

- **Data Structure and Querying**: Databases provide a structured way to organize and query data. With databases, you can define tables, relationships, and indexes, enabling efficient data retrieval and manipulation using SQL queries.
- **Data Integrity and Consistency**: Databases enforce data integrity through features like constraints, unique keys, and referential integrity. This ensures that the data remains consistent and adheres to predefined rules.
- **Concurrency and Transactions**: Databases support concurrent access to data and provide mechanisms like transactions to maintain consistency in case of failures. This is crucial for applications with multiple users or concurrent processes.
- **Scalability**: Databases are designed to scale with increasing amounts of data and users. They offer features like sharding, replication, and clustering to handle growing workloads.
- **Search and Indexing**: Databases support indexing mechanisms that significantly speed up data retrieval. This is particularly important when dealing with large datasets.
- **Security**: Databases provide access control mechanisms to restrict who can access, modify, or delete data. This helps in securing sensitive information.
- **Query Optimization**: Databases have query optimizers that analyze and optimize SQL queries for efficient execution. This ensures that your queries run as quickly as possible, especially as the dataset grows.
- **Backup and Recovery**: Databases offer built-in mechanisms for backup and recovery. This is important for data durability and protection against data loss.
- **Consistent Interfaces**: Databases provide standardized interfaces (SQL) that work across various database management systems, making it easier to switch between different databases if needed.
- **Structured Schema**: Databases require a structured schema, which helps in maintaining a clear organization of your data. This is beneficial for understanding and managing the data over time.

### When using databases, do I need to be tied to a particular programming language?

No, you are not tied to a particular programming language when using databases. Most modern databases support various programming languages through standardized interfaces and drivers. The key technology enabling this flexibility is the use of standardized query languages, such as SQL (Structured Query Language). Here's how it works:

- SQL as a Standardized Interface:
  - SQL is a standardized language for interacting with relational databases. It provides a common syntax and set of operations that can be used across different database management systems (DBMS).
  - Whether you're using Python, Java, C#, or any other programming language, you can issue SQL queries to a database to perform operations like inserting data, querying, updating, or deleting records.
- Database Drivers and APIs:
  - Most databases provide specific drivers or APIs (Application Programming Interfaces) for different programming languages. These drivers act as a bridge between your application code and the database, allowing you to send SQL queries and receive results.
- Programming Language Agnostic:
  - As long as you have a database driver or library for your chosen programming language, you can interact with the database. This makes databases programming language agnostic.
- Common Database Connectivity Libraries:
  - Many programming languages have standard or widely-used libraries for connecting to databases. For example:
    - Python: `sqlite3`, `psycopg2` (PostgreSQL), `mysql-connector` (MySQL), etc.


[aws]: https://aws.amazon.com/what-is/sql/#:~:text=Structured%20query%20language%20(SQL)%20is,relationships%20between%20the%20data%20values.
[datacamp]: https://www.datacamp.com/blog/sql-server-postgresql-mysql-whats-the-difference-where-do-i-start
[datacamp1]: https://www.datacamp.com/blog/is-sql-a-programming-language
[kdnuggets]: https://www.kdnuggets.com/introduction-to-databases-in-data-science
[digitalocean]: https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems
[techtarget]: https://www.techtarget.com/searchdatamanagement/definition/SQL
