# Data_Science_Challenge

## Question 1:

 Given some sample data, write a program to answer the following: (link to data set here https://docs.google.com/spreadsheets/d/16i38oonuX1y1g7C_UAmiK9GkY7cS-64DfiDMNiR41LM/edit#gid=0)
 
 On Shopify, we have exactly 100 sneaker shops, and each of these shops sells only one model of shoe. We want to do some analysis of the average order value (AOV). When we look at orders data over a 30 day window, we naively calculate an AOV of $3145.13. Given that we know these shops are selling sneakers, a relatively affordable item, something seems wrong with our analysis. 

1. Think about what could be going wrong with our calculation. Think about a better way to evaluate this data.
2. What metric would you report for this dataset?
3. What is its value?

## My Answer:

1. We can see that the mean order amount is 3145 which is consistent with the wrong calculation obtained before. However, there is an incredibly large standard deviation of 41282.54, which means that on average, the value vary 41282.54 from the mean, making the mean not a great representation of the AOV. From the quantile of order amount we calculated above, 98% of the sneaker sold were below $800. Becides, order amount and total items are positively correlated which means high order amount is correalted with high number of sneakers sold. From the box plot comparison, we could notice that there are some outliers which could be the reason that skewed up the average order amount.
2. Since we have observed outliers and unusual standard error here, it is more appropriate to consider metrics which would not be influenced by extreme values. Therefore, I would report the meadian as it is more robust against outliers.
3. The AOV would be $284, which seems to be more representable of the AOV of the sneaker shops.

## Question 2: 

For this question you’ll need to use SQL. Follow this link (https://www.w3schools.com/SQL/TRYSQL.ASP?FILENAME=TRYSQL_SELECT_ALL) to access the data set required for the challenge. Please use queries to answer the following questions. Paste your queries along with your final numerical answers below.

1. How many orders were shipped by Speedy Express in total?
2. What is the last name of the employee with the most orders?
3. What product was ordered the most by customers in Germany?

## My Answer:

1. 54 orders were shipped by Speedy Express in total.
2. The last name of the employee with the most orders is Peacock.
3. The product ordered the most by customers in Germany was Boston Crab Meat.
