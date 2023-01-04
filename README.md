# SQL-Tutorials 
date - 4th Jan 2023 
All the SQL Syntax and projects

## Select Statement
SELECT (List of column Names)
FROM [Schema Nema].[Table Name]
WHERE (Condition is True/False)


## Basics
1. Comments starts with '--'
2. While writing where conditions it has to be excat matches.
3.  % sign indicates wild card in Where condition. 
4. * sign means it includes all the tables from dataset
5. To return null participants use IS NULL or IS NOT NULL conditions.
6.  Logical Operators in Where Clause
      a) And - Both Conditions must be true
      b) or  - Atleast one condition must be true
      c) Conditions are evaluated in the order they occur in code
      d) conditions in parenthesis are treated as a single unit and are evaluated together.
     
7. A bit column can store either a 1, representing true, or a 0, representing false. If a column is declared as NOT NULL, data is required in that column.
8. Adding Distinct after select gets rid off duplicate orders in tab;e.

### Joints
1. Joints allows us to use common relationships, such as foreign key relationships to look at data in more than one table in single query.
2. INNER JOINS - Related with PK
      Membership is required in both tables for results to be returned in an INNER JOIN.
3. OUTER JOINS - Related with Foreign Key
      The Order of Anchoring table matters in Outer Joins and Query results change according to it.
4. Inner joins require membership in both tables, while outer joins only require membership in the anchoring table.
5. Both subqueries and inner joins can be used to filter, but an inner join must be used if columns from both tables need to be returned in the query results.



## ShortCuts
1) Ctrl + R - To show/hide Query result panel
2) F5 - Execute
3)
