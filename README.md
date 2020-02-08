# SQL-Injection
Sql-Injection is an attack in which malicious Sql statement are injected into a Sql database.

Sql-Injection is easy to avoid, but still happens often!

If successful, we can read sensitive databases, extract information, modify databases and potentially even get a shell.

# Comman SQL Verbs
Sql statements begin with verbs, lets take a look at a few comman verbs:

SELECT-Retrieve data from a table

INSERT-Adds data to a table

DELETE-Removes data form a table

UPDATE-Modifyies data in a table

DROP-Delete a table --> Very malicious

UNION-Combins data from multiple queries

# Other Comman Terms 
WHERE-Filters records based on specific condation

AND/OR/NOT-Filter records based on multiple conditions

ORDER BY-Sorts records in ascending/decending order

# What happens when we run the following statements?
* SELECT * FROM Users;
* SELECT UserID, UserName FROM Users;
* SELECT * FROM Users WHERE Country-'US';
* SELECT * FROM Users WHERE Country='US' AND UserName='Hannan'

# Special Characters
* ' and " -String delimiters
* --, /* and # -comment delimiters
* * and % -wildcards
* ; -Ends SQL statement
* Plus a bunch of others that follow programmatic logic- =, >, <, (), etc

# Classic Example of SQL-Injection in Burpsuite
![SQL-Injection Through Burpsuite](https://user-images.githubusercontent.com/52100180/74090717-6cf6fb80-4ad0-11ea-83c1-bab743242f01.png)

