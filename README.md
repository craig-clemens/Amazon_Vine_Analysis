# Amazon_Vine_Analysis
 
## Project Overview

Collecting review data from Amazon for sports-related products, the ETL process was conducted using Pyspark while connecting to AWS. The purpose was was to determine if there exists a review bias, specifically a favorable one, from the paid-tier Vine members in the data set.

## Results

The total number of reviews breaksdown as:
* 334 Vine reviews
* 61,614 non-Vine reviews

![Vine_nonVine](https://github.com/craig-clemens/Amazon_Vine_Analysis/blob/main/Resources/Vine_nonVine_Total.PNG)

When it comes to 5-star reivews the difference is:
* 139 Vine reviews
* 32,665 non-Vine reviews

![Paid_Unpaid](https://github.com/craig-clemens/Amazon_Vine_Analysis/blob/main/Resources/Totalpaid_Unpaid_FiveStar.PNG)

Taken in terms of percentage of the total:
* 41.62% of the Vine purchases were 5-stars, and 
* 54.47% of the non-Vine purchases where 5-stars

![5_star_percentage](https://github.com/craig-clemens/Amazon_Vine_Analysis/blob/main/Resources/5_star_percentage.PNG)

## Summary

We can see a 12.85% difference between Vine and non-Vine 5-star reviews showing a lack of bias of positivity from paid-tier Vine customers. However, this ~12% gap is likely a result of a small sample size as the number of paid reviews is significantly less than the un-paid reviews.
