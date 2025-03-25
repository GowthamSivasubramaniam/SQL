Objective:

Combine data from two related tables using JOIN operations.

==============================================================================================
 steps followed

==> created Table named Marks with columns Rollno , subject, marks 
==> used to alter query and added constraint for Foreign key to be roll no from StudentRegister
==> Inserted multiple rows using insert into query
==> Used Select query and retrived the data
==> used inner join on condition  equating "rollno" and displayed it . 
   >> inner join only displays the rows that are common to both like if rollno 110 is not present in marks then 
   it will not be displayed.
==> used Natural join without condition  displayed it . 
   >> unlike inner join , natural join don't need a condition and combines common rows automatically 
   >> works same as inner join.
==> used left join on condition  equating "rollno" and displayed it . 
   >> the left join fetches all the rows from left table and  selects all the rows from right table and add null values 
   if right table does not have a "rollno " that is present in left table. and right join is vice versa
   >> we can also use natural left join without any on condition for the same.

==> used cross join which is the cartisian product of 2 tables . Used for analysis.
==> Self join  can be done through joining same table if we want to equate a column inside a same table.

