# Amazon_Vine_Analysis

## Overview of the Analysis

Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. I had access to approximately 50 datasets, while I had trouble with the mobile applications reviews, I chose the musical instruments instead. We will analyze by using PySpark to perform ETL, connect to an AWS RDS instance and load the data into pgAdmin.

## Results

![line_image](resources/total_reviews.png)
![line_iamge](resources/5_reviews.png)
![line_iamge](resources/5_percentage.png)

- As seen from the images above there was a total of 60 paids review and 14477 non paid reviews.
- There was 34 5 star paid reviews and 8212 5 star nonpaid reviews.
- Finally, the percentage of 5 star reviews for paid and unpaid almost identical. 5 star paid reviews is at 56.66 & and 5 star non paid is at 56.72%

## Summary 

Due to the percentages being similar there is no bias in the Vine program. While these datasets are large one way to seek if there is any bias is looking towards merging different datasets together and then trying to see the breakdown of vine program.
