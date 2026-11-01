# Unit 032 — Theory: What Is the N+1 Problem?
- URL: https://www.freecodecamp.org/learn/relational-databases-v9/lecture-working-with-sql/what-is-the-n-plus-1-problem
## Questions (verbatim, signed-in capture 2026-11-01)
- Q1: What is the N+1 problem? — A technique for optimizing database queries by batching them. / A common performance bottleneck where many small queries are executed in sequence. / A method of indexing database tables for faster retrieval. / A type of database join operation.
- Q2: Why does the N+1 problem occur? — Because the application performs an initial query to get a list of records, then executes an additional query for each record to get more information. / Because the database server is too slow to process queries. / Because the application uses too many database connections. / Because the database tables are not properly indexed.
- Q3: A strategy to reduce the number of database queries when retrieving related data and avoid the N+1 problem involves: — Increasing the database connection pool size. / Optimizing individual SQL queries for speed. / Fetching related data within the initial query using JOIN clauses. / Implementing client-side data filtering and sorting.
## Expected keys (advisory)
- Q1 A common performance bottleneck where many small queries are executed in sequence. · Q2 Because the application performs an initial query to get a list of records, then executes an additional query for each record to get more information. · Q3 Fetching related data within the initial query using JOIN clauses.
