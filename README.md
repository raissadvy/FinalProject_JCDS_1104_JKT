# FinalProject_JCDS_1104_JKT
Final Project Purwadhika Data Science by raissa devy


## %ARABICA COFFEE% Sales Improvement

<br><br>

### Background problem :

Sales and marketing team was challenged by the management to improve the monthly  revenue sales, as the previous month's record was barely reached the target. A data scientist was appointed also to collaborate in this project. Given the data, how can we improve the revenue sales?

### Machine learning objective :

Improve customer's buying rate through product recommendation and personalized promotions from customer segmentation.<br>

### Data used : <br>
__Customer Data__ <br>
2.245 rows & 8 columns <br>
__Sales Data__ <br>
49.894 rows & 14 columns <br>
__Product & Inventory Data__ <br>
2 tables :  <br>
88 rows & 14 columns <br>
307 rows & 7 columns <br><br>

__Source :__ <br>
Coffee Shop Dummy Data  from IBM Cognos <br><br>


### Data processing :
1. Store data in SQL-workbench
2. Pull data with SQLalchemy to Jupyter notebook
3. Cleanse data 
4. Import to mongoDB compass

![alt text](https://github.com/raissadvy/FinalProject_JCDS_1104_JKT/blob/main/Screen%20Shot%202021-03-03%20at%2015.02.33.png)

### Unsupervised machine learning :
![alt text](https://github.com/raissadvy/FinalProject_JCDS_1104_JKT/blob/main/recommender.png)

#### 1. Content-based recommender system
Use cosine-similarity to find similarities between items. <br>
![alt text](https://github.com/raissadvy/FinalProject_JCDS_1104_JKT/blob/main/Screen%20Shot%202021-03-03%20at%2015.02.46.png)

#### 2. Collaborative filtering recommender system
Use scikit-surprise library. Use validation parameters RMSE and MAE. <br>
Tune to find best models.
![alt text](https://github.com/raissadvy/FinalProject_JCDS_1104_JKT/blob/main/Collaborative%20filtering.png)

#### 3. Customer segmentation
Use K-Means clustering to determine the cluster of the customers. Number of K was taken from elbow method score and silhouette score (K=4).
Below is the clustering result : <br>
![alt text](https://github.com/raissadvy/FinalProject_JCDS_1104_JKT/blob/main/Screen%20Shot%202021-03-03%20at%2015.03.12.png)
<br><br>

### Web-app dashboard :
Create visualization with mongoDB Atlas, embed using to web-app, connect using pymongo and deploy to Heroku
![alt text](https://github.com/raissadvy/FinalProject_JCDS_1104_JKT/blob/main/dashboard_1.png?raw=true)

<br>

__Link Dashboard :__ <br>
arabica.raissadevy.com <br>
register with your email, log in with your username and password



