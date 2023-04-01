# Java-Additional-Programs
1.Calculate variance and variance pct given sales data of product for two years like 2022 and 2021.
Product	Sales 2021	Sales 2022
Tea	100	120
Coffee	100	110
Green Tea	75	100

Summay:
•	This Java program calculates the variance and variance percentage between two sets of sales data for the years 2021 and 2022. Here's a detailed explanation of the code
•	The program defines two arrays of sales data for the years 2021 and 2022, with three sales figures in each array
•	The program calls the calculateMean() method to calculate the mean of each year's sales data.
•	The program calls the calculateVariance() method to calculate the variance of each year's sales data, passing in the sales data and mean sales for each year.
•	The program calculates the variance percentage between the two years by subtracting the variance of 2021 from the variance of 2022, dividing the result by the variance of 2021, and then multiplying by 100. This gives the percentage change in variance from 2021 to 2022.
•	Finally, the program prints out the variance and variance percentage for the two years using the printf() method to format the output with two decimal places and a percent sign.
•	The program also includes two helper methods: calculateMean() and calculateVariance(). These methods take an array of doubles as input and return the mean and variance of the values in the array, respectively. The calculateVariance() method calculates the sample variance using the formula sum of squares of deviations / (n - 1), where n is the number of data points. This formula is used because we are working with a sample of data rather than the entire population of sales data.


2.Filter the products which contains the word “Tea” and calculate the total for each year.

Summary:
This program creates a list of products and calculates the total sales for each year for all products that contain the word "Tea" in their name using streams and lambda expressions. It uses the Product class to represent each item in the list and has three fields: name, year, and price. The program filters out all products that do not contain the word "Tea" and then groups the remaining products by year and sums up their prices to calculate the total sales for each year. Finally, it prints out the tea totals by year in the console.

3.	Group the passengers by age. For the given data - group the passengers into 6 age groups
 0-10, 10-20, 20-30,30-40,40-50,50+

Summary:
This program calculates the count of passengers in each age group from a given array of passenger ages. It initializes an array to store the count of passengers in each age group, and then loops through the passenger ages to increment the count of the appropriate age group in the array. Finally, it prints the count of passengers in each age group in a tabular format.

4.A program that will settle bills among the people. For test data, used the below data
Bill 1 - Lunch
Total Amount	2000
Paid By	Balaji
Shared by	Anand, Balaji, Chaitanya, Divya
Bill 2 - Movie ticket
Total Amount	1000
Paid By	Anand
Shared by	Anand, Balaji, Chaitanya, Divya
Bill 3 - snacks (excludes Divya)
Total Amount	750
Paid By	Chaitanya
Shared By	Anand, Balaji, Chaitanya

Summary:
This program calculates the balances owed between a group of friends after splitting bills. The program uses a Map to keep track of each person's balance, and a List of Bills to store the details of each transaction. For each bill, the program calculates the share per person and updates the balances accordingly. Finally, the program prints the balances owed by each person. The Bill class is used to store the details of each transaction.

5.Given a map of student name/ID and their list of scores. Calculate the total score of each student.
Student ID	Score
1	[10,20,10]
2	[10,20,11]

Summary:
The program first creates a map studentScores with student IDs as keys and lists of scores as values. It then creates an empty map studentTotalScores to store the total score of each student.

The program then loops through the entries of studentScores, calculates the total score for each student, and adds the result to the studentTotalScores map.

Finally, the program prints out the total score for each student in a table format with columns for Student ID and Total Score.
