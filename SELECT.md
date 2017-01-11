# Hello, This is a project involving SQL basics
----

## Usage

> Individual project:

    Using PostreSQL and using pgAdmin.

I also used the [Pagila](https://wiki.postgresql.org/wiki/Sample_Databases) popular database example for PostreSQL. 

**Pagila: Based on MySQL's replacement for World, Sakila, which is itself inspired by the Dell DVD Store.**


    After installing both PostreSQL and pgAdmin the Database was created.



# Some of the most common basic operators used in SQL

----

OPERATOR                        |  DESCRIPTION               
----

          ==         | Equal 
          
          >          | Greater than 
          
          <          | Less than 

          >=         | Greater than or equal 

          <=         | Less than or equal 

       <> or !=      | Not equal 

         AND         | Logical operator AND

             OR      | Logical operator OR


       
### SELECT Statement


Using the SELECT statement

Important Note:  The SQL key words should always be in uppercase. This is for ease of readability.

From the dvd store we will use some select statements and other basic query syntax.

For Example:

Let's see what's on the film table.

    -- This is a comment and the semicolon " ; " signifies is the end of a statement.

    -- The asterik symbol " * " means that is grabbing all of it on the table.
    
    SELECT * from film;   

 
Here is the depiction:
![Alt text](https://github.com/PauloRlopez/SQL_Basics/blob/master/Images/filmtable.png?raw= "filmTable")







