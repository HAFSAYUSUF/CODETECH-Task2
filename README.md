# CODETECH-Task2
Name: HAFSA Y
COMPANY:CODETECH IT SOLUTIONS
DOMAIN:SQL
DURATION:DECEMBER TO JANUARY

Online Retail Store Database

This project is a simple database design for an online retail store, including tables for products, customers, orders, and payments.

Tables

- Products: Stores product details (ID, name, price, stock).
- Customers: Stores customer details (ID, name, email).
- Orders: Tracks orders (ID, customer ID, date, total amount).
- Payments: Manages payments (ID, order ID, date, amount).

Example Queries

 Insert a product:

  INSERT INTO Products (ProductName, Price, Stock) VALUES ('Laptop', 1000.00, 50);

Retrieve all orders for a customer:

  SELECT * FROM Orders WHERE CustomerID = 1;


 Setup

1. Clone the repository.
2. Import the SQL script into your database.
3. Run the script to create tables and add data.



