# INVENTORY-MANAGEMENT
## Inferential-statistical Analysis

## Al Bundy's shoe shop. – INVENTORY MANAGEMENT

## Problem Statement (Taken From Udemy Course)

Al Bundy is a U.S. based company established 30 years ago.
It also operates in Canada the U.K. and Germany.
The firm sells mid to high end shoes ranging from 120 to 200 dollars while the shoes are of high quality.
You have lots of inventory never sold.
The shoes collect dust on store shelves.
Inventory management is a common problem.
` Many if not most shops cannot determine the right number of items they need to keep in stock. `
The opposite problem arises too.
Shops don't supply an adequate amount of goods and fail to meet the demand in their market.
For instance you have surely entered a shoe shop but could not buy a specific pair of shoes because they did not have them in stock.
In this example we will examine the opposite problem. Problem of having too much inventory.
This is a more significant problem for the company as it means the company has invested in producing or purchasing the product but could not sell it.
One way to solve this problem is by using confidence intervals.

## Data Description
Database with the `sales information` about Al Bundy shop for the years from `2014 to 2016`.
`There's Invoice Number, Date, country, product ID, and shop, which depends on the country the sell, gender indicates if the product is designed for men or women as shoes differ greatly depending on gender. Next we have shoe size.`
Apart from the US size system I have also included the European and the UK ones so it is easier for you to understand the data.
Finally there is the unit price for that sale and the discount that applies.



## Steps of Inferential Data Analysis

## Step 1: `Determine if that sample or population data`.
 It's obviously a sample not the population of sales given we have just three years of data. We 

## Step 2: Get to know the data set better.

There are two big `subgroups in our data men's shoes and women’s shoes`. They are different and bundling them when making predictions will yield deceiving results as not only the feet differ by gender but also there are different shoe types and models.

Our problem is related to `inventory management`
Therefore we should divide our inventory and then count the frequencies the frequencies will give us a better idea of the data 

A possible solution is to create two tables one for men's shoes and one for women's shoes and then proceed (Check Excel)

We must have normally distributed data.
While this sounds restrictive for all practical applications it isn't.
We can simply apply our good old friend the central limit theorem when we are in the presence of a sum or average of many observations.
We can assume normality in our case we are calculating average sales for a period.
Given that Al Bundy shop has been operating for over 30 years silty applies and we can safely continue with our inference.

##Step 3: Determine the exact problem
Problem: `We want to estimate the number of shoes that are likely to be sold`.

##Step 4: Decide the confidence Level – 
Let Confidence Level = 0.05  
This will give the range of number of shoe pairs required with 95% confidence.

Note:
We have the last 12 months of sales and make a prediction.
We are only doing this only for men's shoes as the main problem is identical for both genders.
Since, people have different shoe sizes we will have to calculate 17 confidence intervals one for each size.

##Step 5: Calculate the Confidence Interval 
Note: The Calculations are done in the Excel sheet attached
5.1	Calculate the means.
5.2	Compute the standard errors 
5.3 Compute the margins of error
5.3	Compute The value of t-statistics : Since, Population Variance is unknown we will use t-statistic

`The t-statistic for a 95 percent confidence interval with 11 degrees of freedom. =2.20` ##Excel Sheet

In 95 percent of the cases, the true population mean of the sales for each shoe size will fall into the respective interval ##
Calculated in excel for 17 shoe sizes) 



As we don't want to be low on stock.
A possible solution to the problem is to get as many pairs of shoes as the closest number to the upper limit of the confidence interval. (Calculated in Excel)
In this way you will be almost certain you won't run out of stock and shoes won't be waiting forever in your storage unit.

