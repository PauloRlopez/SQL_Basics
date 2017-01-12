# COUNT_FUNCTION
----
## How to use it?


> The COUNT (*) function returns the number of items in a group, including NULL values and duplicates that matches a specific condition of a query. 

----
## usage and examples

From the previous database we can grab all the number of items in the payment table like this.


     SELECT COUNT(*) FROM payment;
     
![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/count1.png?raw="count1")

Now we can use it with DISTINCT as well;

     SELECT(DISTINCT amount) 
     FROM payment;

![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/count2.png?raw="count2")

___

## created- changelog 
* 11-January-2017

----
## thanks
* many
