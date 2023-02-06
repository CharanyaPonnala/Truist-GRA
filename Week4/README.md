# Week 4 

## California Housing Dataset

#### Note: 
1) **housing_graph_final.csv** is the name of the dataset file from which we created our graph database. 
2) **Queries** folder contains the codes of the queries that we ran on Neo4j on our graph database. 

We were supposed to create a graph database using Neo4j on the California Housing Dataset.

The California Housing dataset is a popular dataset used in machine learning and statistical modeling. It is a collection of information about housing 
prices and demographics in the state of California. The dataset includes information on various aspects of housing in the area, such as the median house 
value, median income, housing median age, total rooms, and more.

Here is a description of the California Housing Dataset - https://developers.google.com/machine-learning/crash-course/california-housing-data-description

These are the steps that we went through - 

1) Investigated and researched various graph databases and evaluated their features to assess their efficiency on a scale of -5 to +5. 

2) Pre-processed and engineered the California Housing dataset, in which we added additional columns such as "city" which contained cities based on the 
coordinates provided for each blockgroup, and id columns. We added range columns based on median housing age, median housing value, median housing income
by transforming continuous variables into categorical ones through the use of quartile binning. 

3) Created an interconnected graph database using Neo4j by merging relationships between nodes and incorporating attributes. 

4) Visualized the graph database and executed several queries to gain insights and verify its accuracy and consistency.
