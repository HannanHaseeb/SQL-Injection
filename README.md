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
1. SELECT * FROM Users;
2. SELECT UserID, UserName FROM Users;
3. SELECT * FROM Users WHERE Country-'US';
4. SELECT * FROM Users WHERE Country='US' AND UserName='Hannan'

# Special Characters
1. ' and " -String delimiters
2. --, /* and # -comment delimiters
3. * and % -wildcards
4. ; -Ends SQL statement
5. Plus a bunch of others that follow programmatic logic- =, >, <, (), etc

![Image of Yaktocat](https://github.com/HannanHaseeb11/SQL-Injection/edit/file:///root/Pictures/Screenshot%20from%202020-02-08%2022-28-06.png)
