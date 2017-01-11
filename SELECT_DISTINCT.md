
# **SELECT DISTINCT STATEMENT**


**The SELECT DISTINCT STATEMENT**

This statement is used when there is duplicable values but you might want to add only different (distinct) values.

For example:

Let's say we want to find out when all the movies were 
released.

Let's look at the film table first:

    SELECT * FROM film;

Question:
I want to know all the year the movies were released.

We can use the distinct statement like this:

    SELECT DISTINCT release_year FROM film;


I want to know the rental rate of the dvd


    SELECT DISTINCT rental_rate FROM film;


**Exercise example:**

We want to find out the types of ratings movies we have in the United States (e.g PG, PG-13, R, etc...) and which ones do we have in the database.

Thus one way to do this is to obtain the distinct rating types in our films table.

Like this:


    SELECT Statement

    SELECT * FROM film;

    SELECT DISTINCT rating 
    
    FROM film;


Here is the the whole film table.


![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/ex3.png?raw= "filmTable")

After we confirmed there is a rating column, we grabbe it to see the movie ratings: 

![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/ex4.png?raw="filTable")

There!
