# sqlproject
My SQL project that I worked during one of my MBA courses 

This script is a class project that uses SQL queries to perform descriptive statistics on the PopRunner dataset. 
The dataset includes tables for consumers, pop-up messages, purchases, and emails. 
The script begins by displaying the first five rows of each table using the SELECT statement with the LIMIT clause.

Next, several queries are executed to gather descriptive statistics from each table. 
For example, Query 5 calculates the count and average age of consumers by gender. 
Query 6 determines the count and average age of consumers in each loyalty status group. Query 7 examines the number of consumers who received pop-up messages and continued to add discount codes to their cards.

The script then moves on to analyze the purchase table. Query 8 calculates the average amount spent by consumers on their total sales. 
Query 9 determines the number of consumers who opened the email blast.

In the following section, tables are combined using JOIN operations to find answers to specific questions. 
Query 10 evaluates whether the pop-up advertisement was successful by comparing the sales of consumers who received pop-up messages with those who didn't. 
Query 11 investigates whether the consumer with the lowest spending opened the pop-up message using nested queries.

Similarly, Query 12 assesses the success of the email blast by comparing the sales of consumers who opened the email with those who didn't. 
Query 13 examines whether the consumer with the highest spending opened the email message using nested queries.

