# Week 3

## Yelp 

We were supposed to create graph databases using the NetworkX library in Python from the Yelp Dataset acquired from 
https://github.com/librahu/HIN-Datasets-for-Recommendation-and-Network-Embedding.

The .dat files are the Yelp datasets that we procured from the GitHub repository.

**week3_team3_final.ipynb** is the Jupyter notebook file that we implemented our code in. 


1) First we loaded the Yelp dataset into a Pandas DataFrame. Then we performed data preprocessing on our dataframe by splitting columns, and 
renaming columns, and assigning prefixes to values for ease of understanding (since all the data was numeric). 

2) Then using NetworkX package in Python, we created a heterogenous graph containing entities such as User, Business, Compliment, City, Category as nodes
and the relationships between them as edges. 

3) We created edge label attributes based on ratings given by a user to a business.
