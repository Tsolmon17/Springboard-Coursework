Capstone Project 1 Proposal
Default of Credit Card Clients (data set from UCI)

1.	What is the problem you want to solve?

*	Goal is to predict whether the client will default default next month or Column 24

2.	Who is your client and why do they care about this problem?

*	My client in this case would be a bank or a financial institution either assessing their current portfolio of loans or trying to predict if a prospective customer will likely to default.

3.	What data are you going to use for this? How will you acquire this data?

*	This data set has 24 columns containing personal and payment history of credit card customers in Taiwan; Contains 30,000 rows of data
*	Types of variables used: nominal variables (sex), ordinal variables (education, payment history), continues variables (credit amount, payment amount)
*	Column 1 -- amount of credit given (in dollars)
*	Columns 2-5 -- contain personal information (gender, education, age, etc.) as categorical variables represented with numbers. For example, gender (1=male, 2=female), education (1=grad school, 2=college, 3=high school, 4=other)
*	Columns 6-11 -- contain payment history in ordinal variable format from Sep 2005 thru Apr 2005 (-1=paid on Dme, 1=late one month,...9=late nine months of more)
*	Columns 12-17 -- contain billing amounts for last 5 months starDng in Sep 2005 thru Apr 2005 (in dollars)
*	Columns 18-23 -- past 5 month payment amounts starDng in Sep 2005 thru Apr 2005 (in dollars)
*	Column 24 -- default next month (1=yes, 0=no) as a nominal variable
*	This data is from UCI Machine Learning Repository

4.	In brief, outline your approach to solving this problem (knowing that this might change later).

*	I will use some sort of regression algorithm or machine learning to predict the outcome

5.	What are your deliverables?

*	Probably some python codes that will learn in next few weeks
