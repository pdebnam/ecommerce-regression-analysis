# ecommerce-regression-analysis
Analysis of Ecommerce data using Linear Regression model

Scenario:
An Ecommerce company sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.

Goal:
Given customer data they've collected, the company would like to determine whether they should focus their efforts on their mobile app experience or their website

Data:
The dataset provided (Ecommerce Customers.csv) contains string fields for customer infomation, such as Email, Address, and their color Avatar. Additionally, it contains numerical value columns per customer:

Avg. Session Length: Average session of in-store style advice sessions.
Time on App: Average time spent on App in minutes
Time on Website: Average time spent on Website in minutes
Length of Membership: How many years the customer has been a member.
There is also a numerical "Yearly Amount Spent" column, denoting how much a customer spent a year. This will serve as our target/output variable.

Approach:
Visualize the data to identify any trends which stand out through observation
Fit the data to a Linear Regression model in order to analyze the impact of the various input variables on the output of the yearly amount spent per customer
