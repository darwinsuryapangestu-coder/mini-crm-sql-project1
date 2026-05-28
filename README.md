# Mini CRM SQL Project

A simple SQL-based CRM project for managing customers and orders. This project demonstrates basic database structure, relationships, and data filtering using SQL.

## Features
- Customer data management
- Order tracking system
- Shipping status table
- SQL filtering and queries
- Relational database structure

## Database Structure

**Customers**
- customer_id
- first_name
- last_name
- age
- country

**Orders**
- order_id
- item
- amount
- customer_id

**Shippings**
- shipping_id
- status
- customer

## Example Query

```sql
SELECT * FROM Customers
WHERE age > 25;
```

## Skills Demonstrated
- SQL querying (SELECT, WHERE)
- Data filtering and sorting
- Basic relational database design
- Understanding table relationships

## Purpose
This project was created as a learning step to understand how CRM systems store and manage customer data using SQL. It can be expanded into a full sales pipeline system in the future.

## Future Improvements
- Add JOIN queries between tables
- Build sales pipeline stages (Lead, Qualified, Won)
- Add dashboard visualization
- Integrate with frontend (HTML/JS)

## Screenshot at attachment
