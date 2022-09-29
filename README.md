# Amazon_Vine_Analysis
#### Google Colab Notebook, PostgreSQL, pgAdmin 4, AWS

## Overview

This analysis uses PySpark to perform ETL processes to extract data, transform data, connect to an AWS RDS instance, load the data in pgAdmin, and then use the data to determine if there is any positivity bias for reviews in the Vine program.

## Results

1. There are 94 Vine reviews
2. There are 40,471 Non-Vine reviews
3. There are 48 paid 5-Star Vine reviews 
4. There are 15,663 unpaid 5-Star Vine reviews
5. 51% of the Vine reviews were 5-Star reviews
6. 39% of the Non-Vine  reviews were 5-Star reviews

![Results](https://user-images.githubusercontent.com/101427781/192918517-80ea40fd-3f53-44ca-92a9-7380d715384a.png)

## Summary

As shown above in the results section, 51% of the reviews in the Vine program were 5-Star reviews, compared to only Non-Vine reviews with a 5-Star rating of 39%. The data points to a clear positivity bias of reviews in the Vine program. 
