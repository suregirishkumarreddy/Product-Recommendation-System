# Product-Recommendation-System
My Graduate Capstone Project - This is a Product Recommendation System for a Local Wholesaler in India, using Python and Machine Learning 

Dataset :- About two and half years of data used for this project and is uploaded on GitHub (Sales Transactions-2017.csv, Sales Transactions-2018.csv, Sales Transactions-2019.csv)

Used Flask web framework in Python to publish the results on a web page

Link to the web application :- https://product-recommendation-system.herokuapp.com/

About the Project :- https://youtu.be/0FCxHEc_e8Q (This video provides an understanding about the company and the project)


# Program Files
PGM-1 - Data_Cleaning.ipynb                  - Performs Data Cleaning to remove the irrelevant data

PGM-2 - Product_Ranking.ipynb                - Identifies the Top Selling and Most Popular products

PGM-3 - Customer-Product-Ranking.ipynb       - Identifies the products of a Customer, Most frequently purchased and Purchased the Most

PGM-4 - Recommend_Products_to_Customer.ipynb - Identifies the similarities between the customers. This is further used to recommend the products to a Customer, based on the products they purchased and similarities with other Customer purchase pattern

PGM-5 - Recommend_Similar_Products.ipynb     - Identifies the similarities between the products. This correlation is further used to identify the similar products for the item being viewed

These programs create .pkl files (prod_ranking_model.pkl, cust_prod_ranking_model.pkl, cust_correlation_model.pkl, prod_correlation_model.pkl), which are further accessed for publishing data on website

Flask.ipynb   - Python program with different functionalities based on the user action on website, to publish the data on to website
