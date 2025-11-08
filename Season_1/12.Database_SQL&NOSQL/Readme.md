# Databases:
## What is a Database?
- It is an organized collection of data.

## What is a Database Management System?
![alt text](image.png)

- The application connects to the DBMS to Connect to the Database.
- DBMS is a layer which is build on the top of the Database.

## Types of Database:
### 1. Relational DB
  - E.g. MySQL, PostgreSQL

### 2. NoSQL DB
  - E.g. MongoDB

### 3. Graph DB
  - It is a type of NoSQL Database.
  - E.g. Neo4j

### 4. In Memory DB
  - It is used in cases where we have an API which is used very frequently. 
  - It uses in Memory Caching, if the cache memory already has all the data then the API call is not made.
  - E.g. Redis.

### 5. Distributed SQL DB
  - E.g. Cockroach DB

### 6. Time Series DB
  - E.g. Influx DB

### 7. Object Oriented DB
  - E.g. db4o

### 8. Hierarchial DB
  - E.g. IBM IMS(Information Management System)

### 9. Network DB
  - E.g. IDMS

### 10. Cloud DB
  - E.g. Amazon RDS


- An organization can use all the databases based on the requirement.

## Relational Database Management System(RDBMS) ft. MySQL, PostgreSQL
- SQL stands for Structured Query Language, since this language is used to interact with the database.

- EF Codd defined 13 rules for a database to become a Relational Database.

### 1. SQL
- Modern day databases do not follow these rules but they are still Relational Databases.

- Michael Widenius created the software MySQL named after her daughter My Widenius.

- He created 2 more databases with the name of his daughter i.e. Maria DB and Max DB.

- Maria DB is the fork of My DB.

### 2. PosgreSQL
- Michael Stonebreaker was working on Project Ingres in University of California.

- The project was of SQL so it was called PostgreSQL.

## NoSQL Database ft. MongoDB
- It is also called Not SQL or Not only SQL.
- MongoDB was built in 2009.
- There are several types of NoSQL Databases:
  - `Document DB`
    - MongoDB is a document database.
  
  - `Key Value DB`
  
  - `Graph DB`
  
  - `Wide Column DB`
  
  - `Multi Modal DB`

- 10 gen created MongoDB Software.
- Mongo came from Humongous which means huge or gigantic.
- `10 gen` was renamed to `MongoDB`.
- It is very flexible, very compatible with Javascript.
- It stores data in JSON format.
- Developer's productivity increases with MongoDB.

![alt text](image-1.png)

- In RDBMS we have to do join to get the data from multiple tables.

- In RDBMS the data is stored in the normalized manner i.e. without redundancy.

## Difference between the RDBMS(MySQL) and the NoSQL Databases(MongoDB)
```text
 ___________________________________________________________________________________________
|            RDBMS                               NoSQL                                      |
|___________________________________________________________________________________________|
|   1.  Stores data in terms of          |  1. Stores data in terms of Collection           |
|       Tables, Rows and Columns.        |     document and fields.                         |
|                                        |                                                  |
|   2.  Stores data in structured        |  2. Stores data in unstructured format.          |
|       format.                          |                                                  |
|                                        |                                                  |
|   3. It follows fixed schema it        |  3. It is flexible in terms of the schema.       |
|      cannot be changed easily once     |                                                  |
|      build.                            |                                                  |
|                                        |                                                  |
|   4. It uses the Structured Query      |  4. It uses Mongo Query Language(MQL) to         |
|      Language(SQL) to communicate      |     Communicate with the Database for MongoDB,   |
|      with the Database.                |     or (Cypher) to communicate with the Neq4J.   |
|                                        |                                                  |
|   5. Horizontal Scaling is tough.      |  5. Easy to scale horizontally and vertically.   |
|                                        |                                                  |
|   6. There are ralationships like      |  6. There are nested relationship in the NoSQL   |
|      Foreign Keys and Joins in the     |     databases.                                   |
|      RDBMS.                            |                                                  |
|                                        |                                                  |
|   7. These are used for the Read-heavy |  7. These are used for Real Time, Big Data,      |
|      applications, transactions and    |     distributed computing applications.          |
|      workloads.                        |                                                  |
|                                        |                                                  |
|   8. Examples of the RDBMS applications|  8. Examples of NoSQL Applications are Real Time |
|      are Banking apps.                 |     analytics and social media.                  |
|________________________________________|__________________________________________________|
```

