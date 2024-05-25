# Implement-Agglomerative-Hierarchical-Clustering-using-Python
### Table Of Contents
1. Introduction
2. Agglomerative clustering 
3. Algorithm 
4. Data Source
5. Linkage
7. Dendogram

### Data preparation 
- First, we compute the dissimilarity information between each pair of objects in the dataset. This helps us understand the relationships between the objects.
- Next, we use a linkage function to group the objects into a hierarchical cluster tree. This is done based on the distance information generated in the previous step. Objects or clusters that are close to each other are linked together using the linkage function.
- Finally, we determine where to cut the hierarchical tree to create clusters. This process creates a partition of the data, allowing us to analyze and understand the different groups within the dataset.

### Technologies
* Python

## Project Description
### Similarity measures
To decide which objects/data points/clusters should be combined or divided. The method used for measuring the distance of similar objects.

There are many methods to calculate the dissimilarity information, including Euclidean and Manhattan distances. 

The linkage function utilizes the distance information provided by the function to cluster pairs of objects based on their similarity. Subsequently, these clusters are connected to form larger clusters. This iterative process continues until all objects in the initial data set are interconnected in a hierarchical tree structure.

## Needs of this project

The bottom-up approach provides numerous advantages, especially when flexibility, innovation, and detailed insight are of utmost importance. Here are some key benefits of utilizing a bottom-up approach:

1. Enhanced Innovation
2. Increased Employee Engagement
3. Greater Flexibility and Responsiveness
4. Improved Problem-Solving
5. Detailed and Comprehensive Understanding
6. Democratization of the Workplace
7. Better Risk Management
8. Local Optimization

## Data Source : 
https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set 


Ref Articles : 
https://towardsdatascience.com/implement-agglomerative-hierarchical-clustering-with-python-e2d82dc69eeb 
https://medium.com/@khalidassalafy/agglomerative-hierarchical-clustering-a-study-and-implementation-in-python 
