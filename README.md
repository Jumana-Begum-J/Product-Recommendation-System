# Product-Recommendation-System

E-commerce recommendations have two parts. First one is the initial phase when 
the user joins the e-commerce website with no purchasing history. Another is 
when the user has a purchasing history. When the user has no purchasing history 
the e-commerce recommender faces the cold-start problem. In such cases the 
recommender resolves the issue by recommending the most frequently purchased 
items or items with high ratings. And once the user starts purchasing, we aim to 
understand how the recommender recommends highly rated similar products or 
highly rated products bought by similar customers. In this project we are using 
the ratings given to a product by other users to make recommendations to the 
current user. The KNN algorithm is used with Pearson’s Correlation Coefficient 
to make recommendations to the user by predicting the ratings of that user for all 
products and then recommending the top 5 products. Both item based and user 
based KNN recommendations are done and their performances are compared.

# DATASET

The project is implemented based on the AMAZON electronic products rating 
dataset. It has 4 columns:
1. UserID: Every user identified with a unique ID
2. ProductID: Every product identified with a unique ID
3. Rating: Rating of corresponding product by corresponding user
4. Timestamp: Time of the rating
