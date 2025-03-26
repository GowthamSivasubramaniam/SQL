Objective:

Simplify complex queries and process hierarchical data using CTEs.

=========================================================================================================
steps followed

>> with non Recursive cte we can simplify queries like we can make it select a particular thing 
and we can use it with outer query.

>> used cte  named rankedemployees and created rank for employees and 
in outer query used that rank to find the salary difference among the employess in comaparison with lead employees.
if not used the query will be subquery and costs more computation time than ctes.

>> for Recursive cte created a table named employeedetails and had managerid and employeeid along with first and last name
 of employess and inserted values.

>> from there created a anchor expression found managers like if their "managerid is null" they are managers
>> found hierarchy of working , with the main expression by comparing the previous anchor query's results and the table's result
like <cte table>.employeeid = <table's>.managerid and selects all the hierarchy of working like who is working under whom.
