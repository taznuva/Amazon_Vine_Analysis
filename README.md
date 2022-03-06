# Amazon_Vine_Analysis

## Overview
Purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members in chosen dataset. The analysis will be performed by using PySpark, Pandas, and/or SQL. The analysis will also require PySpark to perform ETL on Amazon Product Reviews. 

## Results
- There are 658 Vine reviews and 78,569 non-Vine reviews on this dataset.
- Out 658 Vine reviews, 229 of them were 5 stars and 43,835 5 stars were non-Vine. 
- About 35% 5 star reviews were Vine and nearly 56% 5 star reviews were non-Vine

## Summary
Although Vine reviews do help with receiving overall positivity for the products on this dataset, however, the amount of 5 star Vine reviews hardly made it to get to 50% threshold. Out of 658 Vine reviews, only 35% were 5 stars. Therefore, it's not positively biased. Majority of 5 stars reviews were non-Vine. To find how we can increase the percentage on Vine reviews, we can do further analysis on individual star ratings and see what the average is. 
