# Amazon_Vine_Analysis
Analyze Amazon Vine reviews with PySpark.


.

_____________________________
# Overview of the analysis:
_____________________________



This project is about analyzing the Amazon Vine program and determining If there is a bias in Reviews from Vine members, in this Analysis ,
I did use PySpark to perform the ETL process 


1.  To extract the dataset, 
2.  Transform the data, connect to an AWS RDS instance, and 
3.  Transformed data into Pgadmin also calculate different metrics


The goal of this Analysis is to determine If there is a bias review from Vine members Focused on the US reviews for PC


____________
# Resources 
____________

Software: Google Colab Notebook, PostgreSQL 12.7, pgAdmin 4 


AWS Data Source: Amazon Review datasets, PC Review dataset
_____________
# Results :
______________

_______________________________
__Total number of reviews__
_______________________________



![1](https://user-images.githubusercontent.com/82621077/129494310-c7beed43-9ed6-48d0-a042-32ee68cee429.png)

__4,291 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset__




______________________________________________________________
__Vine reviews were 5 stars/ non-Vine reviews were 5 stars__
_______________________________________________________________



![Total Views](https://user-images.githubusercontent.com/82621077/129494143-afd019cd-32da-4253-9b7d-4f84a57a5ab6.png)

 # 15,663 of the 5-star reviews were non-vine
 # Total of 15711 5-star reviews

_______________________________________________________________________
__Percentage Vine reviews were 5 stars/ non-Vine reviews were 5 stars__
________________________________________________________________________





![Per](https://user-images.githubusercontent.com/82621077/129494293-099bc7bf-aff5-45a4-8e6c-89faabdc2f7d.png)
![1](https://user-images.githubusercontent.com/82621077/129494309-57d32b88-0c7e-44f5-ad16-579fb16fb7e0.png)


# 38.9% of the five_star reviews were non-vine
# 38.2% of the five_star reviews were vine

_________
# Summary
_________

38.2% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 38.9%. We can tell there is only a slight difference between Vine and non Vine reviews  the conclusion of the results    is not  biased 
Additionally, we could analyze the statistical distribution (mean, median, and mode) of the star rating for the Vine and non-Vine reviews..





