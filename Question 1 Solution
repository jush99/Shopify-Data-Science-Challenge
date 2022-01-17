# Shopify-Data-Science-Challenge

Question 1: Given some sample data, write a program to answer the following: click here to access the required data set

On Shopify, we have exactly 100 sneaker shops, and each of these shops sells only one model of shoe. We want to do some analysis of the average order value (AOV). When we look at orders data over a 30 day window, we naively calculate an AOV of $3145.13. Given that we know these shops are selling sneakers, a relatively affordable item, something seems wrong with our analysis. 

# Think about what could be going wrong with our calculation. Think about a better way to evaluate this data. 
# Solution: 
From the description of the data set, we can see that the amount 3145.13 was obtained by taking the average of the order amount column. This amount is large probably because it is the mean, and could be influenced by outliers. We also note that the standard deviation is 41282.54, which is incredibly large, so the values in the data set are further away from the mean. Thus we can see that the mean is not a very good estimate of the AOV.
With the other statistics provided we can see that at the 3rd quartile, 75% of the data points fall under 390. This is much smaller than the AOV of 3145.13. The max value is 704000, which is way larger than the 3rd quartile. So it seems we do indeed have some outliers conrtibuting to the large AOV of 3145.13. 
Also the AOV calculated did not take into consideration the number of shoes bought. It has just divided the sum of order amount with total number of entries. 

Inorder to minimize the error, I thought of calculating the avergae price per pair of shoe bought. This value considers the average price per pair and hence gives a view as to what could be the price per pair sold. Here we can even identify the outlier that is the amount equal to 25725. I dropped the value where the average price per shoe is greater than that. This makes sure that the outlier is absent and we could conduct further analysis to understand why the value 25725 is present. It could a misprint while enetering data or there is some suspicious activity going on.


# What metric would you report for this dataset?
I would report the average price per pair of shoe sold. This considers price per pair and does not take into consideration the outliners.

# What is its value?
It's value is 307.011
