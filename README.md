# Amazon Vine Analysis

## Overview
### Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results
### Number of Reviews
#### * Vine Reviews: 0
#### ![image](https://github.com/slafton/Amazon_Vine_Analysis/blob/main/Images/Paid%20Votes%20Dataframe.png)

#### * Non-Vine Reviews: 403,807
#### ![image](https://github.com/slafton/Amazon_Vine_Analysis/blob/main/Images/UnPaid%20Votes%20Dataframe.png)


### 5 Star Reviews
#### * 5 Star Vine Reviews: 0
#### * 5 Star Non-Vine Reviews: 242,889

### Percentage of 5 Star Reviews
#### * Percentage of 5 Star Vine Reviews: 0.00%
#### * Percentage of 5 Star Non-Vine Reviews: 60.15%

## Summary 
### From our results we have no reviews from the Vine Program from this dataset. This analysis does not show any bias toward favorable reviews from Vine members. For further analysis I would recommend computing the average of the star ratings.