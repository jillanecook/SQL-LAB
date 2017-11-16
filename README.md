# SQL-LAB

SQL LAB 

JILLANE COOK

1.  SELECT * FROM customers;

2.  SELECT DISTINCT country FROM customers;

3.  SELECT * FROM customers WHERE customerId LIKE '%BL%';

4.  SELECT * FROM orders LIMIT 100;

5.  SELECT * FROM customers WHERE postalCode = '1010' OR postalCode ='3012' OR postalCode = '12209' OR postalCode ='05023';

6.  SELECT * FROM orders WHERE shipregion <> NULL;

7.  SELECT * FROM customers ORDER BY country,city;

8.  INSERT INTO customers values ('AAAAA', 'COOK DESIGN', 'JILLANE COOK', 'SALES', '2071 OAKWOOD', 'GRAND RAPIDS', 'NULL', '49505', 'UNITED STATES', '(616)291-3473', '(616)291-3474');

9.  UPDATE orders
	SET shipregion = 'EuroZone'
	WHERE shipcountry = 'France'
 
10. DELETE FROM order_details WHERE 
quantity = '1';

11. SELECT orderid,MIN (quantity), MAX (quantity), AVG (quantity) from order_details

12.  SELECT orderid, MIN (quantity), MAX (quantity), AVG (quantity) from order_details GROUP BY orderid;
    
13. SELECT * FROM orders
WHERE orderID = 10290; 
