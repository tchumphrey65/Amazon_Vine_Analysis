# Amazon_Vine_Analysis

## Amazon Reviews ETL - Deliverable 1

### 1. Create Amazon Review DataFrame in Coloab

The data frame extracted is as shown:

![Amazon review dataframe ](https://user-images.githubusercontent.com/91839403/158079623-52dac214-d446-4854-a4ba-10c02504f1e0.jpg)

### 2. Create tables as listed in the Schema for SQL Database

Customer Table

![customer_id _dataframe](https://user-images.githubusercontent.com/91839403/158079663-ccba60ab-4543-46c6-ade2-4d593c461816.jpg)


Product Table

![Products_Dataframe](https://user-images.githubusercontent.com/91839403/158079670-0d62470e-96bd-4722-bc69-f3d5b592e4f4.jpg)


Review Table

![review_id_dataframe](https://user-images.githubusercontent.com/91839403/158079676-b6827020-99d5-4643-9c5e-0a3e2fe355e4.jpg)


Vine Table

![Vine_dataframe](https://user-images.githubusercontent.com/91839403/158079692-a0a56abc-7eae-4490-8db6-d29555deb19d.jpg)

### 3. Dataframes are created as Tables in PGAdmin SQL Database

SQL Queries

![SQL_Queries](https://user-images.githubusercontent.com/91839403/158079950-cb9079c5-4482-483d-aa7d-c4cedda98dc9.jpg)

Customer Table

![Customer_SQL_Table](https://user-images.githubusercontent.com/91839403/158079970-6496dd05-1f09-44cf-8cfa-c1f9379c599c.jpg)


Product Table

![products_SQL_table](https://user-images.githubusercontent.com/91839403/158079985-d1e5a31f-3c2a-4370-abc8-9d6e98dbbc05.jpg)


Review Table

![review_id_SQL_table](https://user-images.githubusercontent.com/91839403/158079993-24a1fb86-aa4c-4119-b676-8cb44356c1fb.jpg)


Vine Table

![Vine_SQL_Table](https://user-images.githubusercontent.com/91839403/158079996-773c7a13-59c5-4ed3-8d90-ca65c9a2e506.jpg)


## Amazon Reviews ETL - Deliverable 2

### Dataframes created, Filtered ( >20 and >50% positive) 

Vine Dataframe

![Del2_vine_table](https://user-images.githubusercontent.com/91839403/158082749-b196d8f5-a6dd-41e4-b9c9-a7e8c8da83f9.jpg)


Dataframe filtered to create a DataFrame where total votes > 20 votes.

![Del2_vine_table_20](https://user-images.githubusercontent.com/91839403/158082842-459cf32d-f998-4dcc-98be-8063a0dc00f7.jpg)

Dataframe filtered to create a DataFrame where percentage of helpful_votes is greater than or equal to 50%

![del2_vine_table_50pct](https://user-images.githubusercontent.com/91839403/158082891-7cf139a3-caf9-410e-a4c1-75f41692e944.jpg)

Dataframe filtered to create a DataFrame where there is a Vine review

![del2_vine_Y](https://user-images.githubusercontent.com/91839403/158082938-6418bdd3-511e-4fad-adec-9be423b99761.jpg)

Dataframe filtered to create a DataFrame where there is not a Vine review

![Del2_vine_N](https://user-images.githubusercontent.com/91839403/158082967-27165ecf-47ab-46b9-8158-fd0fc8b3cc2b.jpg)

Data analysis to calculate total number of reviews, 5 Star reviews and percentages for both Vine and Non-Vine reviews 

![review_analysis_totals](https://user-images.githubusercontent.com/91839403/158083010-2c35f30b-b0e9-4628-bd3f-f3a9b4522926.jpg)

Percentage of 5 Star reviews

![Percentage_five_star_reviews](https://user-images.githubusercontent.com/91839403/158083048-22f549d5-1623-48a0-bbe3-cf02beffb537.jpg)




