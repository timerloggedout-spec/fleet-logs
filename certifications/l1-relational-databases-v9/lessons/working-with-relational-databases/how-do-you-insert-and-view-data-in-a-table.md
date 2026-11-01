# Unit 018 — Theory: How Do You Insert and View Data in a Table?
- URL: https://www.freecodecamp.org/learn/relational-databases-v9/lecture-working-with-relational-databases/how-do-you-insert-and-view-data-in-a-table
## Questions (verbatim, signed-in capture 2026-11-01)
- Q1: What does the asterisk (*) represent in the SQL statement SELECT * FROM products;? — It selects the last column from the products table. / It indicates that there is an error in the SQL query. / It selects all columns from the products table. / It selects all rows where a column contains the asterisk character.
- Q2: Which SQL command is used to add a new record to a table named products? — SELECT name, price FROM products; / INSERT INTO products (name, price) VALUES ('New Product', 4.5); / UPDATE products SET name = 'New Product' WHERE price = 4.5; / CREATE TABLE products (name VARCHAR(100), price DECIMAL);
- Q3: Given the following query: SELECT price FROM products WHERE category='Laptops'; What is the main purpose of the WHERE category = 'Laptops' clause? — To specify that only the price column should be displayed. / To sort the resulting list of products based on their category. / To filter the rows, returning only the products whose category is 'Laptops'. / To update the category of all products to 'Laptops'.
## Expected keys (advisory)
- Q1 It selects all columns from the products table. · Q2 INSERT INTO products (name, price) VALUES ('New Product', 4.5); · Q3 To filter the rows, returning only the products whose category is 'Laptops'.
