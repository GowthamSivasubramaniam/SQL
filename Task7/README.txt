objective

Leverage window functions to perform calculations across a set of rows.

=========================================================================================

steps followed

>> created a table named employess with name , departmet and salary
>> inserted respective values
>> used window function rank() and created a employe rank with respective to each dapartment with the 
help of partition by created rank like higher salary will have higerrank acheived ordering with orderby
 >> rank() skips continues rank if Duplicate rank is found like 1,1,3,4

>> used window function Dense_Rank() and created a employe rank with respective to each dapartment with the 
help of partition by created rank like higher salary will have higerrank acheived ordering with orderby
 >> Dense_rank()  continues rank evenif Duplicate rank is found like 1,1,2,3

>> used window function row_number() ehich provided a unique number for each row in incremental manner based 
on partition by clause

>> used lead and lag to tarck next person'salary and previous persons salary and created a salary difference 
basedvon rank