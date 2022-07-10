# Amazon Vine Analysis

## Purpose 

The purpose of this project is to analyze reviews from Amazon Vine members. Amazon Vine invites the most trusted reviewers on Amazon to post opinions about products to help their fellow customers make informed purchase decisions. Among 50 data sets, I selected the Video Games data set to use PySpark and perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark, Pandas, and SQL to determine if there is any bias toward favorable reviews from Vine members in the Video Games dataset. 

## Results 

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

* There were 40565 total reviews, 40471 non-Vine reviews and 94 vine reviews 
<img width="680" alt="Screen Shot 2022-07-10 at 7 22 26 AM" src="https://user-images.githubusercontent.com/95447175/178146730-b5649a0e-76f0-44e6-85e0-8ba7d593d128.png">

<img width="673" alt="Screen Shot 2022-07-10 at 7 23 01 AM" src="https://user-images.githubusercontent.com/95447175/178146742-00324aec-bd9c-4783-8b87-64436e050737.png">

* 15663 non-Vine reviews were 5 stars, and 48 Vine reviews were 5 stars 

* About 39% of non-Vine reviews were 5 star reviews, and 51% of Vine reviews were 5 star reviews 

<img width="547" alt="Screen Shot 2022-07-10 at 7 24 32 AM" src="https://user-images.githubusercontent.com/95447175/178146800-9ab0e704-8785-407d-ad96-8635589daf5c.png">

## Summary

The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)


<img width="294" alt="Screen Shot 2022-07-09 at 8 42 56 PM" src="https://user-images.githubusercontent.com/95447175/178129743-68ab85a2-57d5-4ffd-8aab-f1b3abf083dd.png">

<img width="659" alt="Screen Shot 2022-07-09 at 8 43 31 PM" src="https://user-images.githubusercontent.com/95447175/178129747-8cfa0103-c8af-45e5-913c-184a2c1636bb.png">

<img width="492" alt="Screen Shot 2022-07-09 at 9 08 32 PM" src="https://user-images.githubusercontent.com/95447175/178129749-ef7baad9-30ad-4629-9749-465e54f05080.png">

