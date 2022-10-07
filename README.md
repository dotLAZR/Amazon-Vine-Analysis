# Amazon-Vine-Analysis

### Overview
*  Using one of these datasets (Sports Reviews) in order to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset. 


### Results
* There were a total of 467 paid reviews
* The percentage of 5 ratings of paid reviews is 39.82%

* There was a total of 93,420 unpaid reviews
* The percentage of 5 star ratings of unpaid reviews is 51.62%

* Looking at possible bias is it easy to say there was no bias from the percentage of 5 star reviews compared to total reviews. Looking further into the data we see there were many more unpaid reviews which skews the data. 
