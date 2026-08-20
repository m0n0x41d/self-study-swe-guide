---
icon: server
---

# DBMS & SQL!

Data modelling and SQL are core skills for most software engineers, including frontend engineers who need to understand the APIs and data behind an interface.

SQL starts as a small declarative language and becomes deeper as you learn relational modelling, query planning, transactions, and concurrency.

Start with `SELECT`, but do not stop there.

Learn and practise:

* tables, rows, columns, keys, and relationships;
* normalization and deliberate denormalization;
* constraints and why the database should protect valid state;
* `SELECT`, filtering, joins, grouping, subqueries, and common table expressions;
* inserts, updates, deletes, and migrations;
* transactions, isolation, and concurrency failures;
* indexes and how to inspect a query plan;
* safe parameterized queries from your programming language;
* backups and the difference between storing data and being able to recover it.

Your default study materials on the topic:

1. Alan Beaulieu's "Learning SQL" for a coherent introduction
2. The [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html) or the documentation for the database you install locally
3. SQL problems on HackerRank or Codewars for query practice

Before moving on, design a small relational schema, load realistic test data, write non-trivial queries, add a useful index, and show the difference in the query plan. Explain which invariants the schema enforces and which remain in application code.
