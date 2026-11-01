# Answers to FreeCodeCamp Relational Databases v9 Lesson

## Key Answers:
KEY Q1: It selects all columns from the products table.
KEY Q2: INSERT INTO products (name, price) VALUES ('New Product', 4.5)
KEY Q3: To filter the rows, returning only the products whose category is 'Laptops'.

## Question and Answers:

### Q1
**What does the asterisk (*) represent in the SQL statement SELECT * FROM products;?**

**Correct Option:** It selects all columns from the products table.

**Justification:** The asterisk (*) in an SQL SELECT statement is a wildcard character that represents all columns in the specified table.

**Evidence:** *"The asterisk (*) is a wildcard character that represents all columns in the table."*

---

### Q2
**Which SQL command is used to add a new record to a table named products?**

**Correct Option:** INSERT INTO products (name, price) VALUES ('New Product', 4.5)

**Justification:** The INSERT INTO statement is used to add new records to a table, specifying the column names and values for the new row.

**Evidence:** *"To add a new record to a table, use the INSERT INTO statement. For example: INSERT INTO products (name, price) VALUES ('New Product', 4.5);"*

---

### Q3
**Given the following query: SELECT price FROM products WHERE category='Laptops'; What is the main purpose of the WHERE category = 'Laptops' clause?**

**Correct Option:** To filter the rows, returning only the products whose category is 'Laptops'.

**Justification:** The WHERE clause in an SQL query filters the rows based on a specified condition, in this case, selecting only the products with the category 'Laptops'.

**Evidence:** *"The WHERE clause filters the rows based on a condition. For example, the following query returns only the products whose category is 'Laptops': SELECT price FROM products WHERE category='Laptops';"*