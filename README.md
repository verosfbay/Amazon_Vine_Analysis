# Amazon Vine Analysis

## Purpose 

The purpose of this project is to analyze reviews from Amazon Vine members. Amazon Vine invites the most trusted reviewers on Amazon to post opinions about products to help their fellow customers make informed purchase decisions. Among 50 data sets, I selected the Video Games data set to use PySpark and perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark, Pandas, and SQL to determine if there is any bias toward favorable reviews from Vine members in the Video Games dataset. 

## Results 

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

* There were 40565 total reviews, 40471 non-Vine reviews and 94 vine reviews 

* 15663 non-Vine reviews were 5 stars, and 48 Vine reviews were 5 stars 

* About 39% of non-Vine reviews were 5 star reviews, and 51% of Vine reviews were 5 star reviews 

## Summary

The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)


<img width="294" alt="Screen Shot 2022-07-09 at 8 42 56 PM" src="https://user-images.githubusercontent.com/95447175/178129743-68ab85a2-57d5-4ffd-8aab-f1b3abf083dd.png">

<img width="659" alt="Screen Shot 2022-07-09 at 8 43 31 PM" src="https://user-images.githubusercontent.com/95447175/178129747-8cfa0103-c8af-45e5-913c-184a2c1636bb.png">

<img width="492" alt="Screen Shot 2022-07-09 at 9 08 32 PM" src="https://user-images.githubusercontent.com/95447175/178129749-ef7baad9-30ad-4629-9749-465e54f05080.png">

