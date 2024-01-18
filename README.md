# Database Lessons


## Databases

**[A database][datacamp1] is a storage system to house your structured data**. It can be a:

- File-based database: It is a single file on your local machine, with the extension name `.db`, `.sqlite`, etc. You can open this file with database viewer to see its structure.
- Directory-based database: Other database systems use directories to store their data. Inside these directories, you will find multiple files that make up the database.
- Server-Based database: Some databases are managed by a database server, and the actual data files may be stored in a location defined by the server.

### Relational database structure

[A relational database][aws] stores information in tabular form, with rows and columns representing different data attributes and the various **relationships between the data values**.

![](./assets/relational-databases.svg)

## Database management system (DBMS) and relational database management system (RDBMS)

A database management system (DBMS) is a sofware that serves as an interface between the database and its end-users or programs. The most common type of DBMS is a relational database management system (RDBMS).

## Structured Query Language (SQL)

[SQL][datacamp] is the standard programming language for interacting with relational databases. With SQL, you can query, or ask questions of, the data in a relational database. You can use SQL statements to store, update, remove, search, and retrieve information from the database. You can also use SQL to maintain and optimize database performance.

SQL was invented in the 1970s based on the relational data model. It was initially known as the structured English query language (SEQUEL). The term was later shortened to SQL. Oracle, formerly known as Relational Software, became the first vendor to offer a commercial SQL relational database management system.

> The term SQL is pronounced ess-kew-ell or sequel.

SQL queries and other operations take the form of commands written as statements and are aggregated into programs that enable users to add, modify or retrieve data from database tables.

## What are RDBMS?

[RDBMS is] a collection of programs and capabilities that enable IT teams and others to create, update, administer and otherwise interact with a relational database. **RDBMSes store data in the form of tables**, with most commercial relational database management systems using Structured Query Language (SQL) to access the database.


## RDBMS vs. DBMS

An RDBMS is a type of database management system (DBMS) that stores data in a row-based table structure which connects related data elements. Here are the main

[RDBMS is]: https://www.techtarget.com/searchdatamanagement/definition/RDBMS-relational-database-management-system
[aws]: https://aws.amazon.com/what-is/sql/#:~:text=Structured%20query%20language%20(SQL)%20is,relationships%20between%20the%20data%20values.
[datacamp]: https://www.datacamp.com/blog/sql-server-postgresql-mysql-whats-the-difference-where-do-i-start
[datacamp1]: https://www.datacamp.com/blog/is-sql-a-programming-language
