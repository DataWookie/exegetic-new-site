---
title: "Introduction to SQL"
topic: true
subjects: ['Database']
subjects_weight: 10
draft: false
intro: |
  If you want to build a successful career in Data Science, you'll need to learn the basics of SQL. Writing an SQL query is very often the first step in an analysis. If you can write a solid SQL query then you're already well on your way.
duration: 1 day
who: The course is suitable for anybody who needs to work with data in a relational database.
objectives: In this course you'll learn how to perform CRUD (Create, Read, Update and Delete) operations on a relational database.
outcomes: Participants will be able to create and populate tables, perform moderately complex queries, update and delete records on a relational database.
requirements: |
  Familiarity with spreadsheets will be helpful but not essential.
setup: |
  - Install [DBeaver](https://dbeaver.io/download/).
---

<!--
https://www.khanacademy.org/computing/computer-programming/sql
https://www.stat.berkeley.edu/~spector/sql.pdf
https://www.datacamp.com/courses/intro-to-sql-for-data-science
https://www.pluralsight.com/courses/introduction-to-sql
-->

### Data Query

Using SQL to execute queries against a Relational Database.

- What is SQL?
- SQL syntax
	- Code layout
	- Comments
- Retrieving data using `SELECT`
	- Grabbing all the fields
	- Selecting specific fields
	- Aliases
- Selecting specific records
	- Just the first few results
	- `WHERE` for filtering
	- Logical predicates
	- Matching portions of strings with `LIKE`
	- Checking for set membership with `IN`
	- `DISTINCT`
	- `CASE`
	- Working with missing (`NULL`) data
- Sorting with `ORDER BY`
- Aggregation
	- `GROUP BY`
	- Selected functions for aggregations: `MIN`, `MAX`, `COUNT`, `SUM` and `AVG`
	- Filtering after aggregation with `HAVING`
- Join
	- Why normalise?
	- `INNER JOIN`
	- `LEFT JOIN`, `RIGHT JOIN` and `FULL JOIN`

### Data Definition

Using SQL to create the structure of a Relational Database.

- `CREATE` a database
- Tables
	- `CREATE` a table
	- Column types
	- Constraints
		- `NOT NULL`
		- `UNIQUE`
		- `CHECK`
	- Index
	- Primary and Foreign keys
	- Auto increment
	- Default values
- Cleaning up
	- Dropping a table
	- Dropping a database

### Data Manipulation

Using SQL to manipulate data in a Relational Database.

- `INSERT` - Putting data into tables
- `UPDATE` - Changing existing data
- `DELETE` - Removing data