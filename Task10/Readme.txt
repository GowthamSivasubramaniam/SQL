objectives

Design a normalized database schema for a complex business scenario (e.g., an eCommerce platform) and 
implement advanced SQL features to ensure performance, data integrity, and automation.

===========================================================================================

>> created 3 tables named orders,Customer and Product
>> where created a trigger named "decrease_quantity" whenever an insert in orders table takes place
it will automatically decreases product's Quantity from product table
>> Also created another trigger named "check_quantity" when an insert in order table is going to happen it checks the 
amount of Quantity ordered is available and allows the insert or abort it based on availablility.
>> simulated transactions like rollbacking an order if customer cancels it before commit.
>> created view named order_summary to dispaly the customer and product details.
>>created index on order with date whenever a date is used in where it filters based on this index.

===========================================================================================
