
# SELECT Statement


Using the SELECT statement

Important Note:  The SQL key words should always be in uppercase. This is for ease of readability.

From the dvd store we will use some select statements and other basic query syntax.

For Example:

Let's see what's on the film table.

    -- This is a comment and the semicolon " ; " signifies is the end of a statement.

    -- The asterik symbol " * " means that is grabbing all of it on the table.
    
    SELECT * FROM film;   

 
Here is the depiction:
![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/filmtable.png?raw= "filmTable")



**Other Example:**

Question:

We want to send out a promotional email
to our existing customers!  For this we would need their emails and names.

Solution:

Looking at the customer table first:

    SELECT * FROM customer;

Then, after I look at what I might need from the customer table:

     -- in two columns to make more readable…

    SELECT first_name, last_name, email 

    FROM customer;
It might look like this:
This is a fictitious data thus we are not compromising anyone.

![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/ex2.png?raw= "filmTable")




