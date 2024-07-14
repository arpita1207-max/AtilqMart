```
Bussiness Problem 
The Supply Chain team has adopted a standardized approach to measure service levels. This includes the daily measurement of 'On-time delivery (OT) %',
'In-full delivery (IF) %', and 'On-Time in Full (OTIF) %' for customer orders, benchmarked against the target service levels established for each customer.
```

```
Solution Approach
There are 3 dimension tables: dim_customers, dim_products, dim_date and 2 fact tables: fact_orders_line, fact_orders_aggregate.
Power BI is used as the visualization tool in this project.
The data is imported, analyzed, and transformed in the Power Query Editor.
The relationships between the tables have been created in Power Pivot.
```

```
Solution Approch
I have create few measures for the KPI:-
Sno	Measures		               Description
1	Total Order Lines		         Count of all order lines in fact_orders table
2	Line Fill Rate	             Number of order lines shipped In Full Quantity / Total Order Lines
3	Volume Fill Rate	           Total Quantity shipped / Total Quantity Ordered
4	Total Orders		             Total Orders placd
5	On Time Delivery %	         Number of orders delivered On Time / Total Number of Orders
6	In Full Delivery %	         Number of orders delivered in Full quantity / Total Number of Orders
7	On Time In Full %	           Number of orders delivered both IN Full & On Time / Total Number of Orders
8	On Time Target 		           Average of On-Time Target 
9	In Full Target 		           Average of In-Full Target
10 On Time In Full Target 		 Average of OTIF Target


AtliqMart Report




TOP LEVEL KPIs

![TOP LEVEL KPIs](https://github.com/user-attachments/assets/40430bfe-371d-4623-9e07-9e43d2d88e4f)
````
