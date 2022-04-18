# Amazon_Vine_Analysis
## Overview Of Analysis
> This analysis based on analyzing the Amazon reviews written by members of the paid Amazon Vine program. We`ve been given 50 datasets and randomly picked one for ETL process on the Vine Program to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.Later on we tried to determine if there is a bias toward favorable reviews from Vine members in given dataset. "Chosen topic was Office Products."
## Results
>First part is Creating a server, database and download the data from the source. This part was done by Pyspark Google Colab. Then append the table on server in the PgAdmin. <br />
![Picture1](/Resources/customers_table.png) <br />

![Picture2](/Resources/products_table.png)<br />

![Picture3](/Resources/review_id_table.png)<br />

![Picture4](/Resources/vine_table.png)<br />
> Second part is shown in following image which include the numbers and percantage relation paid and unpaid reviews. <br />
> ![Picture5](/Resources/Percentage.png)<br />
>Among the total 969 paid reviews only 430 ones are fives star. On the other hand there are total 43745 unpaid reviews which 19233 are five starts.
## Summary
> Paid percentage on the five star reviews is slightly higher than the unpaid ones. Since the difference is small, it is not efficient to say there are bias toward favorable reviews on Office Products. Also on Office Products Reviews may not be participated in Vine Program too much. %44.37 are the paid five star reviews ratio to the total ones,  % 43,96 is the unpaid ratio on the same category.
