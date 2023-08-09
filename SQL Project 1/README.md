# Sakila DVD Rental database Analysis
PDSND - Udacity Project One:  Investigating a Relational Database
 

## Introduction

The Sakila Database holds information about a company that rents movie DVDs. In this project, the Sakila DVD Rental database was queried to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. For assistance in the queries, the schema for the DVD Rental database was used as given in the `dvd-rental-erd.pdf`.


Source: http://www.postgresqltutorial.com/postgresql-sample-database/

Supporting Material: https://video.udacity-data.com/topher/2018/September/5ba96b12_dvd-rental-erd-2/dvd-rental-erd-2.pdf

## Local Environment Setup 

Option 1 was used: 

Option 1:
We have set up the DVD Rental database within the Classroom Workspace to allow you to run your queries on the database. We encourage you to use the Workspace within your classroom. __ If you are short on time, and don't have at least a couple of hours available to set up the database, we strongly recommend using the Workspace within your classroom.__ If you prefer to use the classroom workspace, jump ahead to the concept titled "Composite Key".

Option 2:
Alternately, you can run the queries on your local machine using a new database system, PostgreSQL. Please keep in mind - this option requires setting aside at least a couple of hours to set up the PostgreSQL database. Also, you may find learning to set up a PostgreSQL database on your local machine involves a sharp learning curve. Learning how to set up and use PostgreSQL is a valuable skill to add to your data analyst skill set, so the time you spend on it will be worth it.

If you choose Option 2, you will have two additional tasks to complete:

a) You will need to install the new database system, PostgreSQL.

b) You will need to load the database in your local PostgreSQL database server.


## Questions worked upon for analysis

**Question 1**

We want to understand more about the movies that families are watching. The following categories are considered family movies: Animation, Children, Classics, Comedy, Family and Music.

**Create a query that lists each movie, the film category it is classified in, and the number of times it has been rented out.**

**Question 2**

Now we need to know how the length of rental duration of these family-friendly movies compares to the duration that all movies are rented for. **Can you provide a table with the movie titles and divide them into 4 levels (first_quarter, second_quarter, third_quarter, and final_quarter) based on the quartiles (25%, 50%, 75%) of the rental duration for movies across all categories?** Make sure to also indicate the category that these family-friendly movies fall into.


**Question 3**

We want to find out how the two stores compare in their count of rental orders during every month for all the years we have data for. **Write a query that returns the store ID for the store, the year and month and the number of rental orders each store has fulfilled for that month.**
Your table should include a column for each of the following: year, month, store ID and count of rental orders fulfilled during that month.
**The count of rental orders is sorted in descending order.** 

**Question 4** 

We would like to know who were our top 10 paying customers, how many payments they made on a monthly basis during 2007, and what was the amount of the monthly payments. Can you write a query to capture the customer name, month and year of payment, and total payment amount for each month by these top 10 paying customers?