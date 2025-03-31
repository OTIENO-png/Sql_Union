##SQL_UNION
The UNION operator is used to combine the result-set of two or more SELECT statements. Every SELECT statement within UNION must have the same number of columns The columns must also have similar data types The columns in every SELECT statement must also be Purpose of the Query
This SQL query retrieves a combined list of unique employee IDs from two tables: Employee_Data and Department_Data. It uses the UNION operator to merge the results and automatically remove duplicates.in the same order

##BREAKDOWN OF THE CODE
#First SELECT Statement:
SELECT Employee_id_No FROM Employee_Data
Fetches all Employee_id_No values from the Employee_Data table.

#Second SELECT Statement:
SELECT Employee_id_No FROM Department_Data
Fetches all Employee_id_No values from the Department_Data table.

UNION Operator:Combines the results of the two SELECT statements.
Removes duplicate entries, ensuring each Employee_id_No appears only once in the final result.
