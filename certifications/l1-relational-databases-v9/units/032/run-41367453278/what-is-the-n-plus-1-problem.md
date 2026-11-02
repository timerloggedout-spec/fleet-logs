KEY Q1: A common performance bottleneck where many small queries are executed in sequence.
Q1: What is the N+1 problem?
A: A common performance bottleneck where many small queries are executed in sequence.
Justification: The lesson defines the N+1 problem as a performance issue caused by executing multiple small queries sequentially.
Lesson evidence: "The N+1 problem is a common performance bottleneck where many small queries are executed in sequence."

KEY Q2: Because the application performs an initial query to get a list of records, then executes an additional query for each record to get more information.
Q2: Why does the N+1 problem occur?
A: Because the application performs an initial query to get a list of records, then executes an additional query for each record to get more information.
Justification: The lesson explains that the N+1 problem occurs when an application makes an initial query followed by additional queries for each record.
Lesson evidence: "The N+1 problem occurs when an application performs an initial query to get a list of records, then executes an additional query for each record to get more information."

KEY Q3: Fetching related data within the initial query using JOIN clauses.
Q3: A strategy to reduce the number of database queries when retrieving related data and avoid the N+1 problem involves:
A: Fetching related data within the initial query using JOIN clauses.
Justification: The lesson suggests using JOIN clauses to fetch related data in the initial query as a strategy to avoid the N+1 problem.
Lesson evidence: "One strategy to reduce the number of database queries when retrieving related data and avoid the N+1 problem is to fetch related data within the initial query using JOIN clauses."