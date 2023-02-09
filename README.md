## Hackerrank SQL Questions and Solutions 

#### **Question 1:**

The data for the number of employees from several famous IT companies is maintained in the "COMPANY" table. Write a SQL query to print the IDs of the companies that have more than 10000 employees in an ascending order. 

**Solution**

```sql 
SELECT  ID  

FROM COMPANY 

WHERE employees > 10000 

ORDER BY ID ASC;
```

