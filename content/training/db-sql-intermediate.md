---
title: "Intermediate SQL"
topic: true
subjects: ['Database']
subjects_weight: 10
draft: true
---

## Course Description

### Data Query

Using SQL to execute queries against a Relational Database.

- Union
- Subqueries
	- `EXISTS`
	- `ANY` and `ALL`

### Data Definition

Using SQL to create the structure of a Relational Database.

- Normalisation
- Changing table structure with `ALTER`
	- Adding and removing columns
	- Specifying column position (`AFTER` and `FIRST`)
	- Adding a primary key
- Renaming a table
- Views

### Performance

<!-- https://dev.mysql.com/doc/refman/5.5/en/execution-plan-information.html -->

- The query optimiser
- Query plan
- Writing better queries
- Indexes
	- `CREATE INDEX` – Adding an index
	- The benefits of an index
	- The costs of an index
	- `DROP INDEX` – Deleting an index

### Data Manipulation

Using SQL to manipulate data in a Relational Database.

- Mixing `UPDATE` with `JOIN`

### Transaction Control

Using SQL transactions to ensure database integrity and process isolation.

- Why use transactions?
- Managing transactions
	- `COMMIT`
	- `SAVEPOINT`
	- `ROLLBACK`

### Users

- Creating users
- Access control with `GRANT` and `REVOKE`