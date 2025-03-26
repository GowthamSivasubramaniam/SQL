objective

Manipulate and query data based on date and time values.

=========================================================================================

steps followed

>> created 3 tables orders,customer,product
>> where had a column named date where used "datetime" datatype
>> added custom dates to order with date_sub(now(), interval "no of days" day) 
>> also displayed the Delivery date by adding (the Order_date + 10) by date_add() function
>> also filterd using date_sub with 30 days to show orders within 30 days.
>> And displayed how many days since today the order was made with datediff(now(),ordered date)
>> Also converted date to this format dd/mm/yyyy with  DATE_FORMAT(date, '%d/%m/%Y')
>> And  converted date to dd-mon-yyyy with  DATE_FORMAT(Orders.date, '%d-%b-%Y')