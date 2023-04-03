# Amazon_Vine_Analysis

## project objective: 
Analyzing beauty product reviews on Amazon Vine

## dataset: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Beauty_v1_00.tsv.gz

## methodology: 
1. Created database with Amazon RDS
2. Create schema in pgAdmin using schema.sql (in folder) 
3. Cleaned/transformed data from S3 bucket using Google Colab (Amazon_Reviews_ETL.ipynb)
4. Imported cleaned tables into pgAdmin 

4 tables were created for this database: 
review_id table
![review_id_table](https://user-images.githubusercontent.com/113721712/229587929-00bd98a0-df65-49c9-bba0-f38e2dfdf068.png)

vine_table
![vine_table](https://user-images.githubusercontent.com/113721712/229593186-0c87b4cc-6f61-43e9-a215-18708443a273.png)

customer_table
![customers_table](https://user-images.githubusercontent.com/113721712/229593208-ba91a44a-6577-41e0-b1c2-fd9b97e4a1dd.png)

products_table 
![Products_table](https://user-images.githubusercontent.com/113721712/229594269-7d781b64-db06-4088-9e75-9bfbb4217da9.png)





