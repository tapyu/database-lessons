# Structured Query Language (SQL)

### Introduction

**[SQL][aws] is a declarative, [domain-specific][datacamp] programming language** for storing and processing information in a relational database. [It][datacamp] is designed for managing data using **SQL queries**. A query is nothing but a statement consisting of various SQL commands that together perform a specific task to access, manage, modify, update, control, and organize your data.

> The term SQL is pronounced ess-kew-ell or sequel.

### History

[Edgar Frank Codd][datacamp], a British computer scientist working at IBM, published a paper called “A Relational Model of Data for Large Shared Data Banks” in 1970. This is when he invented the relational model for database management, which **has served as the theoretical basis for relational databases and relational database management systems (RDBMS)** ever since. 

Following this, efforts were made to create an official SQL standard in the late 1980s. SQL became a standard of the American National Standards Institute (ANSI) in 1986 and of the International Organization for Standardization (ISO) in 1987. The SQL standard has been revised multiple times since the 1980s, although the core features of the standard SQL have been stable since 1992.

However, as different vendors implemented their own RDBMS, they introduced variations or extensions to the SQL language to meet specific requirements or take advantage of unique features. **Today there exists only one SQL language, but the different Relational Database Management Systems (RDBMS) have extended the original SQL standard to add their own functionalities or adapt the syntax to their own way of functioning. By doing so, they gave birth to a variety of SQL dialects.**

### Key ideas

- SQL is the language used to communicate with and manipulate data within an RDBMS.
- RDBMS is a software system that organizes and manages structured data using tables, following the relational model for efficient storage, retrieval, and manipulation. Examples include MySQL, PostgreSQL, SQLite, Oracle, and SQL Server.
- As RDBMS were evolving over the time, different variations of SQL were created, thus forming the SQL dialects.
- When you use an RDBMS, you typically write SQL statements to define the structure of the database, query and manipulate data, and control access to the database.

---

# Database management systems (DBMS)

## Relational database management systems (RDBMS)

![image](https://github.com/tapyu/database-lessons/assets/22801918/29b687af-9931-4536-b4cc-f6f85438b0dd)
Data is from 2023.


## NoSQL

[NoSQL][aws] refers to non-relational databases that don't use tables to store data. Developers store information in different types of NoSQL databases, including graphs, documents, and key-values. NoSQL databases are popular for modern applications because they are horizontally scalable. Horizontal scaling means increasing the processing power by adding more computers that run NoSQL software.

## Time Series Databases

TODO: kdnuggets

# Database for Machine Learning

The choice of a database for Machine Learning (ML) datasets depends on various factors, including the nature of the data, the size of the dataset, the types of queries or analyses you need to perform, and the requirements of your machine learning workflow. Here are some considerations for selecting a suitable database for ML datasets:

- Size and Structure of the Dataset: If your ML dataset is structured and fits well into tabular formats, a relational database like PostgreSQL or MySQL may be appropriate. These databases are well-suited for structured data with defined relationships.
- Flexibility and Schema-less Datasets: For datasets with a more flexible or schema-less structure, NoSQL databases like MongoDB or Elasticsearch might be suitable. They can handle semi-structured or unstructured data, making them flexible for diverse data types.
- Scalability: If your ML dataset is expected to grow significantly in size, consider databases with good scalability features. NoSQL databases like Apache Cassandra or Amazon DynamoDB are designed for horizontal scalability, allowing them to handle large datasets.
- Complex Queries and Analytics: For complex queries and advanced analytics, a database with strong querying capabilities is essential. Both relational databases (with SQL) and certain NoSQL databases (e.g., Elasticsearch) offer powerful query languages for analytics.
- Data Versioning and Lineage: If tracking data versioning and lineage is crucial for your ML workflow, consider using databases that support these features. Some version control systems or specialized databases may provide mechanisms for managing data versions.
- Data Preprocessing and Transformation: Databases that support efficient data preprocessing and transformation can streamline your ML pipeline. Apache Spark, which can work with various storage systems, is commonly used for large-scale data processing and transformation.
- Integration with ML Frameworks: Consider how well the database integrates with your chosen ML framework. Some ML frameworks have connectors or support for specific databases, making data loading and manipulation more seamless.
- Cloud vs. On-Premises: If you are working in a cloud environment, consider cloud-native databases that integrate well with cloud services. Services like Amazon Aurora, Google Cloud Bigtable, or Azure Cosmos DB are cloud-managed databases suitable for ML workloads.
It's important to note that in many ML workflows, data is often preprocessed and transformed before being fed into machine learning algorithms. As a result, the choice of a database is just one part of the overall data management strategy in an ML pipeline. The specific requirements of your ML project will guide the selection of the most suitable database for your needs.

[datacamp]: https://www.datacamp.com/blog/is-sql-a-programming-language
[datacamp1]: https://www.datacamp.com/blog/sql-server-postgresql-mysql-whats-the-difference-where-do-i-start
[aws]: https://aws.amazon.com/what-is/sql/#:~:text=Structured%20query%20language%20(SQL)%20is,relationships%20between%20the%20data%20values.
