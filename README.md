# Data_Analytics_Tasks
for initial setup, please install requirements to follow along

``pip3 isntall -r requirements.txt``

### Quiz01
in the first quiz, I'm working on developers survey data from StackOverflow,
you can find the .zip file in the directory as well, in the jupiter notebook you'll find

- different ways to read data from dataframe
- select specific rows and columns from df
- set desired columns as an index (in my case I am using **ResponseId**)
- create filters and select data using those filters
    1. we can find developers from India or USA who have worked with Python
- sorting values in a df using one or multiple columns
    1. in this case, we are using Age and yearly salary
- do statistical analysis on the data
    1. calculate avg yearly salary of USA developers
  2. calcualte standard deviation, least and most work experience in years of Swiss developers
- create graphs, three graphs you will find in my program are:
  1. developers average salary by their age
  2. georgian developers and their average salary based on their experience
  3. heatmap of every programming language ever used by the developers in total

### Quiz02
In the second quiz, I am working with **LoanStatus.csv** file, 
the following .ipynb file does the following things:
- running analytical function on ApplicationIncome and LoanAmmount columns
- calculating probabilities of loan approval in different scenarios
- creating a graph for Applicant income and Loan amount
- finds percentage of users whose income is less then 2000
- creates bar plot of Loan amounts based on education level of the client
- creates bar plot of income based on their living and working area
- uses t-test to see if avg applicant income is less then a given threshold
- uses t-test to compare two groups with their income amount