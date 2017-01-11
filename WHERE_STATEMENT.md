# WHERE STATEMENT


The WHERE statement is used in conjunction with the SELECT statement and some LOGICAL OPERATORS.
It's mostly used when you want to grab an specific value.

For instance, in our DVD database there are a lot of prices for the DVD rental of a movie.  Let's say we want to find an specifics price for movie rentals.

What are the payments for a rental amount (greater than 11) dollars?

    SELECT * FROM payment
    WHERE amount  > 11;
    
 
 ![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/ex5.png?raw= "ex5")

Other example:

Same as above but we are going to look for amounts not equal to 13.99, like this:

    SELECT amount, payment_date 
    FROM payment 
    WHERE amount <> 13.99;
    
![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/ex6.png?raw="ex6")

####   **SELECT WHERE CHALLENGE**

1.  How many customers have the first name Jared?


        SELECT first_name, last_name FROM customer
        WHERE first_name = 'Jared';
        
![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/challenge1.png?raw="challenge1")

2. What’s the email for the customer with the name Nancy Thomas?

         SELECT email, first_name, last_name FROM customer
         WHERE first_name = 'Nancy' AND last_name ='Thomas';
           
         or we can try:

         SELECT email FROM customer
         WHERE first_name = 'Nancy'
         AND last_name = 'Thomas';
         
![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/challenge2.png?raw"challenge2")

3.  A customer wants to know what the movie “Outlaw Hanky” is about. Could you give them the description for the movie “Outlaw Hanky”?


        SELECT description FROM film
        WHERE title = 'Outlaw Hanky';
![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/challenge3.png?raw="challenge3")

4. A customer is late on their movie return.  I know their address is ‘259 Ipoh Drive.’  I want to call them to let them know.   Can you get me the phone number for the person who lives at ‘259 Ipoh Drive’?

         SELECT phone FROM address
         WHERE address = '259 Ipoh Drive';

![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/challenge4.png?raw="challenge4")

