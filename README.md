# Amazon_Vine_Analysis

## Project Overview
The purpose of the project is to pick one of the S3 datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, using PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, write a summary of the analysis for Jennifer to submit to the SellBy stakeholders. For this part I used Mobile_Electronics, since the one used for ETL analysis didnt have any paid Vine reviews available.

## Results
Vine Summary Dataframe: 
![Vine_Summary](https://github.com/k2handa/Amazon_Vine_Analysis/blob/main/Image%202020-10-21%20at%202.03%20PM.png)

There were 4 paid reviews and 1064 nonpaid reviews. 

There were 1 paid reviews were 5 stars and 527 unpaid reviews were 5 stars.

There were 25% of paid reviews were 5 stars and 50% of unpaid reviews were 5 stars.


## Summary
There was no positivity bias for reviews in the Vine program. The percentage of unpaid 5 stars reviews was 25% more than paid 5 stars reviews.

