# Advanced Selects


Select method is used to retrieve data from a table


We can use AGGREGATE FUNCTIONS, ORGANIZING CLAUSES, AND JOINS with SELECT to create more powerful and flexible commands to help solve complex business problems and extract meaningful insights


## AGGREGATE FUNCTIONS:

- Used to perform calculations on multiple rows and return single result
- Ex. sum, avg, max, min, count
- ex. Select sum(column_name) AS Alias_Name from table_name


## ORGANIZING CLAUSES:

- Used to perform searches and return results in a specific structure
- Ex. Order By, Group By, Having
- Ex.   Select column1, aggregate_function(column_2)
        From table_name
        Group By column_1;


## JOINS:

- Used to deliver information that needs to be combined from more than one table
- Ex. inner join, left join, right join, full join


### Inner Join

- Return rows where there is a match in both tables
- Ex.   SELECT STUDENT.Name, ENROLL.Course_ID
        FROM STUDENT
        INNER JOIN ENROLL ON
        STUDENT.Student_ID = ENROLL.Student_ID


### Left Join

- Return all rows from the left table, and the matching rows from the right table. If there is no match, NULL values are returned from the right table.
- Ex.   SELECT STUDENT.Name, ENROLL.Course_ID
        FROM STUDENT
        LEFT JOIN ENROLL ON
        STUDENT.Student_ID = ENROLL.Student_ID


### Right Join

- Return all rows from the right table, and the matching rows from the left table. If there is no match, NULL values are returned from the left table.
- Ex.   SELECT STUDENT.Name, ENROLL.Course_ID
        FROM STUDENT
        RIGHT JOIN ENROLL ON
        STUDENT.Student_ID = ENROLL.Student_ID


### Full Join

- Return all rows from both tables. If there is no match, return NULL for the missing data in either table
- Ex.   SELECT STUDENT.Name, ENROLL.Course_ID
        FROM STUDENT
        FULL JOIN ENROLL ON
        STUDENT.Student_ID = ENROLL.Student_ID