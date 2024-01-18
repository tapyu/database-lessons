# Databases

**[A database][datacamp1] is a storage system to house your structured data**. It can be a:

- File-based database: It is a single file on your local machine, with the extension name `.db`, `.sqlite`, etc. You can open this file with database viewer to see its structure.
- Directory-based database: Other database systems use directories to store their data. Inside these directories, you will find multiple files that make up the database.
- Server-Based database: Some databases are managed by a database server, and the actual data files may be stored in a location defined by the server.

### Relational database structure

[A relational database][aws] stores information in tabular form, with rows and columns representing different data attributes and the various **relationships between the data values**.

![](./assets/relational-databases.svg)

---

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

[aws]: https://aws.amazon.com/what-is/sql/#:~:text=Structured%20query%20language%20(SQL)%20is,relationships%20between%20the%20data%20values.
[datacamp1]: https://www.datacamp.com/blog/is-sql-a-programming-language
