objective

Encapsulate business logic using stored procedures and functions

===============================================================================
steps followed

=> created a procedure named sales with 2 dates as input and returned the total sales values of each product

=> created a function named discount and make it deterministic and returned the discounted value 

>> the procedures will return results of queries like select,delete,update etc 
>> the function only returns a single value and used for computations
>> if the functionn is deterministic, it returns same value for same inputs.
>> if it is non deterministic, it return differnt values like a function is said to be non deterministic if it uses dates and 
random values because functions like now() will generate differnt dates based on time we use and also rand() function creates 
differnt numbers whenever we call . so these are non deterministic functions.

