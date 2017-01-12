# COUNT_FUNCTION
----
## How to use it?


> The COUNT (*) function returns the number of items in a group, including NULL values and duplicates that matches a specific condition of a query. 

----
## usage and examples

From the previous database we can grab all the number of items in the payment table like this.


     SELECT COUNT(*) FROM payment;

Now we can use it with DISTINCT as well;

     SELECT(DISTINCT amount) 
     FROM payment;

___

## created- changelog 
* 11-January-2017

----
## thanks
* many
