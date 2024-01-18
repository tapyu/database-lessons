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

# Relational database management systems (RDBMS)

|         |  Vendor |
| ---     |   ---   |
| `MySQL` | Oracle  |
| `PostgreSQL` | PostgreSQL Global Development Group |
| `SQL Server` | 	Microsoft |
| `SQLite` |	D. Richard Hipp |

[datacamp]: https://www.datacamp.com/blog/is-sql-a-programming-language
[datacamp1]: https://www.datacamp.com/blog/sql-server-postgresql-mysql-whats-the-difference-where-do-i-start
[aws]: https://aws.amazon.com/what-is/sql/#:~:text=Structured%20query%20language%20(SQL)%20is,relationships%20between%20the%20data%20values.
