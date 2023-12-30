[Check queries overview](#Queries-Overview)      [Bottom of the file](#Conclusion)

# SQL Queries Project
This project consists of a series of SQL queries that demonstrate various scenarios and challenges commonly encountered in database management. The queries cover topics such as data retrieval, analysis, and manipulation using the Sakila database, a sample database for a fictional DVD rental store.

## How to Use

1. **Database Setup:**
    - Download the Sakila database from the [dvdrental.tar](./dvdrental.tar) or [dvdrental.zip](./dvdrental.zip) file.
    - Extract the database file using appropriate tools.

2. **Database Connection:**
    - Use a PostgreSQL database management tool (e.g., pgAdmin, DBeaver) to create a new database.
    - Import the Sakila database into your PostgreSQL server using the extracted SQL file.

3. **Explore Queries:**
    - Each SQL query is stored in a separate file (e.g., `question-1.sql`, `question-2.sql`).
    - Use the links in the [Query Overview](#Queries-Overview) section to navigate through the SQL query files
    - Open the desired query file to view and copy the SQL statement.

4. **Execute Queries:**
    - Paste the copied SQL statement into your PostgreSQL query tool.
    - Execute the query to see the results.

5. **Additional Resources:**
    - Explore the provided database diagram in [printable-postgresql-sample-database-diagram.pdf](./printable-postgresql-sample-database-diagram.pdf) for a visual representation of the database structure.


## Queries Overview

### Question 1

- **Objective:** Display customer names that share the same address (e.g., husband and wife).
- **Query:** [See Question 1 Query](Queries/question-1.sql)

### Question 2

- **Objective:** Find the customer who made the highest total payments.
- **Query:** [See Question 2 Query](Queries/question-2.sql)

### Question 3

- **Objective:** Identify the most rented movies.
- **Query:** [See Question 3 Query](Queries/question-3.sql)

### Question 4

- **Objective:** List movies that have been rented.
- **Query:** [See Question 4 Query](Queries/question-4.sql)

### Question 5

- **Objective:** List movies that have not been rented so far.
- **Query:** [See Question 5 Query](Queries/question-5.sql)

### Question 6

- **Objective:** Identify customers who have not rented any movies.
- **Query:** [See Question 6 Query](Queries/question-6.sql)

### Question 7

- **Objective:** Display each movie and the number of times it got rented.
- **Query:** [See Question 7 Query](Queries/question-7.sql)

### Question 8

- **Objective:** Show the number of films each actor acted in.
- **Query:** [See Question 8 Query](Queries/question-8.sql)

### Question 9

- **Objective:** Display the names of actors that acted in more than 20 movies.
- **Query:** [See Question 9 Query](Queries/question-9.sql)

### Question 10

- **Objective:** For movies rated "PG," show each movie and the number of times it got rented.
- **Query:** [See Question 10 Query](Queries/question-10.sql)

### Question 11

- **Objective:** Display movies offered for rent in store_id and not offered in store_id 2.
- **Query:** [See Question 11 Query](Queries/question-11.sql)

### Question 12

- **Objective:** Display movies offered for rent in either of the two stores (store 1 and 2).
- **Query:** [See Question 12 Query](Queries/question-12.sql)

### Question 13

- **Objective:** Display movie titles offered in both stores simultaneously.
- **Query:** [See Question 13 Query](Queries/question-13.sql)

### Question 14

- **Objective:** Show the movie title for the most rented movie in the store with store_id 1.
- **Query:** [See Question 14 Query](Queries/question-14.sql)

### Question 15

- **Objective:** Determine how many movies are not offered for rent in stores 1 and 2.
- **Query:** [See Question 15 Query](Queries/question-15.sql)

### Question 16

- **Objective:** Show the number of rented movies under each rating.
- **Query:** [See Question 16 Query](Queries/question-16.sql)

### Question 17

- **Objective:** Show the profit of each of the stores 1 and 2.
- **Query:** [See Question 17 Query](Queries/question-17.sql)

## Conclusion

This project serves as a comprehensive example of SQL queries covering a variety of scenarios. The queries are designed to showcase common tasks in database management and can be used as a reference for learning and practicing SQL skills.

Feel free to explore and adapt the queries to your specific needs!

[Go to the top of the page](#SQL-Queries-Project)
