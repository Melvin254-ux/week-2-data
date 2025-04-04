
Here are the SQL queries based on your requirements:

1. Retrieve the `checkNumber`, `paymentDate`, and `amount` from the `payments` table:
```sql
SELECT checkNumber, paymentDate, amount
FROM payments;
```

2. Retrieve the `orderDate`, `requiredDate`, and `status` of orders that are currently 'In Process' from the `orders` table. Sort the results in descending order of `orderDate`:
```sql
SELECT orderDate, requiredDate, status
FROM orders
WHERE status = 'In Process'
ORDER BY orderDate DESC;
```

3. Display the `firstName`, `lastName`, and `email` of employees whose job title is 'Sales Rep' and order them in descending order of `employeeNumber`:
```sql
SELECT firstName, lastName, email
FROM employees
WHERE jobTitle = 'Sales Rep'
ORDER BY employeeNumber DESC;
```

4. Retrieve all the columns and records from the `offices` table:
```sql
SELECT *
FROM offices;
```

5. Fetch the `productName` and `quantityInStock` from the `products` table. Sort the results in ascending order of `buyPrice` and limit the output to 5 records:
```sql
SELECT productName, quantityInStock
FROM products
ORDER BY buyPrice ASC
LIMIT 5;
```
