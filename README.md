
# SQL Interview Questions  - Quiz


## Introduction

This quiz contains questions on topics you can expect to see in an interview pertaining to SQL and Relational Databases. Some of them are multiple choice, while some are short answer. For these short answer questions, double click on the Jupyter Notebook and type your answer below the line. 

## Question 1

What are the 4 main datatypes in SQLite3? Can we use other common types from other kinds of SQL?

Type your answer below this line:
TEXT, INTER, NUMERIC, VARCHAR, BOOLEAN
_______________________________________________________________________________________________________________________________





## Question 2

Explain the relationship between **Primary Keys** and **Foreign Keys**.

Type your answer below this line:
_Referential Integrity: The primary purpose of Foreign Keys is to maintain referential integrity between related tables. This means that for every value in the Foreign Key column of one table, there must exist a corresponding value in the Primary Key column of another table.

Establishing Relationships: By linking a Foreign Key to a Primary Key, you establish a relationship between two tables. This relationship can be:

One-to-One: A row in one table is related to exactly one row in another table.
One-to-Many: A row in one table can be related to multiple rows in another table.
Many-to-Many: Rows in both tables can be related to multiple rows in the other table, often facilitated through a junction table.
_________________________________________________________________________________________





## Question 3

Explain the different types of relationships entities can have in a SQL database. 

Type your answer below this line:
In a SQL database, entities (which are typically represented as tables) can have different types of relationships with each other. These relationships define how data across tables is related and interconnected. The main types of relationships in a SQL database are:

1. One-to-One Relationship:
Definition: A one-to-one relationship exists when each record in Table A is associated with exactly one record in Table B, and vice versa.
Example: Suppose you have two tables, EmployeeDetails and EmployeeContracts, where each employee has exactly one contract. Each record in EmployeeDetails corresponds to exactly one record in EmployeeContracts, and vice versa.
2. One-to-Many Relationship:
Definition: A one-to-many relationship exists when one record in Table A can be associated with one or more records in Table B, but each record in Table B is associated with at most one record in Table A.
Example: Consider a Department table and an Employee table. Each department can have multiple employees, but each employee belongs to only one department. So, each record in the Department table can relate to multiple records in the Employee table (one-to-many).
3. Many-to-One Relationship:
Definition: A many-to-one relationship is essentially the reverse of a one-to-many relationship. It exists when multiple records in Table A can be associated with one record in Table B.
Example: Using the same Employee and Department example, this relationship can be viewed from the perspective of the Employee table. Many employees can belong to the same department (many-to-one).
4. Many-to-Many Relationship:
Definition: A many-to-many relationship exists when multiple records in Table A can be associated with multiple records in Table B. This type of relationship is implemented using a junction table (also known as an associative or linking table).
Example: Consider Students and Courses tables. A student can enroll in multiple courses, and each course can have multiple students enrolled. To represent this relationship, a junction table Enrollment would typically be used, which stores pairs of student IDs and course IDs.
Key Points:
Normalization: Understanding and properly implementing these relationships is crucial for database normalization, which aims to reduce redundancy and improve data integrity.

Referential Integrity: Relationships are enforced through the use of Primary Keys and Foreign Keys, ensuring that data in related tables remains consistent.

Querying and Joins: SQL queries often involve joining tables based on these relationships to retrieve related data efficiently.

Data Modeling: Effective data modeling involves identifying and defining these relationships based on the nature of the data and business requirements.

In summary, understanding these types of relationships allows database designers and developers to structure databases effectively, ensuring data integrity, optimizing queries, and facilitating the management and retrieval of related data in SQL databases.
_______________________________________________________________________________________________________________________________


## Question 4

Explain the various types of JOINs possible with SQL. 

Type your answer below this line:
_______________________________________________________________________________________________________________________________



## Question 5

Explain the relationship between Aggregate functions and GROUP BY statements.

Type your answer below this line:
_______________________________________________________________________________________________________________________________



## Question 6

What role do Associative Entities play (JOIN Tables) in many-to-many JOINs?


Type your answer below this line:
_______________________________________________________________________________________________________________________________



## Summary

In this lesson, we practiced answering open-ended interview questions for SQL and Relational Databases. 
