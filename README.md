# Amazon_Vine
To analyze Big Data on an Amazon dataset, use ETL, Amazon Web Services, and Spark.

## Overview of Project
Manufacturers and publishers can earn reviews for their products through the Amazon Vine program. Members of Amazon Vine are given products by companies like SellBy for a nominal fee in exchange for their reviews, which are subsequently published by these companies. Our job was to connect to an AWS RDS instance, extract the dataset using PySpark, alter the data, then put the modified data into pgAdmin. We examined our dataset using PySpark to see if there was any bias favoring positive reviews from Vine users.

## Results
- Total 47 Vine Reviews
- Total 8362 non-Vine Reviews
- 15 Vine reviews were 5 Stars
- 4332 non-Vine reviews were 5 Stars
- 32% of Vine reviews were 5 Stars
- 51.8% of non-Vine reviews were 5 Stars

## Project Summary
- For this product, the Amazon Vine program was obviously ineffective.
- Compared to Vine reviews, more non-Vine reviews had five stars.
- Based on the aforementioned findings, there were more non-vine reviews than vine reviews in the dataset for evaluations of watches.
- We can get the mean and medians for the same to further corroborate this study.
