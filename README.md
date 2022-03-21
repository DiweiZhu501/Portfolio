# Portfolio
- Author @Diwei Zhu
- Current student of Master's of Management in Analytics, McGill Univeristy 
- LinkedIn: www.linkedin.com/in/diwei-zhu-693132186
- Will be graduating in August 2022



---
## [1. Data Modelling, Optimization, and Machine Learning Projects (Python)](https://github.com/JuniperZhuDiwei/Python-DataScience-ML)
### [1.1. Life expectancy prediction and causality interpretation](https://github.com/JuniperZhuDiwei/Python-DataScience-ML/tree/main/modeling-CausalML-life-expectancy)
- **Keywords : Random Forest, CausalML**
- Trained random forest model to predict life expectancy of countries.
  -  *geographical region*, *gini coefficient*, *hiv rate*, *polio (Pol3) immunization coverage*, *thinness among children* are the five most influential features of life expectancy.
- Checked whether the geographical location “African continent” has causal relationship to lower life expectancy.
  - Observed an approximate 5 years difference in mean (average) life expectancy between countries in Africa and other countries. Objectively speaking, ATE result indicate a possible causality between an African country and having a lower life expectancy value.

  - CausalML feature influence visualization (SHAP values):
    
    <img src="https://drive.google.com/uc?export=view&id=1bR3ehiGhWvyBOq3Q01Oc6zoEMiuAQmDg" width="350" height="300">


### [1.2. Telco churn rate analysis](https://github.com/JuniperZhuDiwei/Python-DataScience-ML/tree/main/TelcoChurn-prediction-optimization)
- **Keywords : LightGBM, Gurobi optimization, Coupon promotion strategy, CausalML**
- Group project (8 members)
- Built and compared models for predicting whether or not a customer is likely to churn. Picked lightGBM by F1 scores.
  -  F1 scores of models
  
  <img src="https://drive.google.com/uc?export=view&id=1FkUjKdHQc5jErUuUtya22tpa6AyZUSIb" width="350" height="150">
  
- Identified best coupon promotion strategy that minimizes loss in monetary value by churns with Gurobi optimization tool
  - Expected monetary value of optimized coupon promotion with predictive result by lighGBM: $24032.70



### [1.3. Predicting success of Kickstarter projects](https://github.com/JuniperZhuDiwei/Python-DataScience-ML/tree/main/Kickstarter-classification-clustering-modelling)
- **Keywords: Classification model, KMeans clustering, Gradient Boosting**
- Predicted success/fail of Kickstarter projects with GBT model (after comparing with Random Forest and KNN in terms of accuracy)
  -  *goal*, *number of days between launch and create*, *length of project names* are the three most influential features.

- Assigned projects into three clusters by three selected features (Used Silhouette and Elbow to determine the number of clusters). 
  - describing characteristics of clusters: 
    
  <img src="https://drive.google.com/uc?export=view&id=16M6GLR2kW8yrmbNJm37ZkIS7-LGn2Cat" width="600" height="120">
  
  
### [1.4. Optimizing Toronto police patrolling routes with Gurobi](https://github.com/JuniperZhuDiwei/Python-DataScience-ML/tree/main/Gurobi-optimization-police-patrol)
- **Keywords: Gurobi optimization, Route planning, Travelling salesman problem**
- Group project (5 members)
- Planned the optimal police car patrolling routes that link Toronto police divisions under imaginary budget limitation and patrolling time restriction
  -  Visualized patrolling routes for two police cars:
  
  <img src="https://drive.google.com/uc?export=view&id=1PyOfGAPsfsBLZ59rS_9pHxU9eyMh4zP1" width="400" height="280">

---
## [2. DBMS Projects (MySQL)](https://github.com/JuniperZhuDiwei/MySQL-dbms)
### [2.1. Creating and querying of wonderland visitors database](https://github.com/JuniperZhuDiwei/MySQL-dbms/tree/main/LaRonde-db-creating-queries)
- **Keywords: MySQL, Build relational database, Queries**
- Built relational database of La Ronde wonderland visitor and facility records in MySQL and generated queries for business insights
  -  i.e. preferences of visitors of different age groups, profiles of most loyal/returning visitors, most popular ticket types
  -  ERD:

  <img src="https://raw.githubusercontent.com/JuniperZhuDiwei/MySQL-dbms/main/LaRonde-db-creating-queries/La%20Ronde_ERD.png" width="600" height="380">
- Appended external weather data from Statistics Canada for in-depth analysis
  

### [2.2. Creating and querying of bumble app user information and matching database](https://github.com/JuniperZhuDiwei/MySQL-dbms/tree/main/group-Bumble-db-creating-queries)
- **Keywords: MySQL, Build relational database, Queries**
- Group project (5 members)
- Built relational database of psuedo user informations and matching records of Bumble dating app and facility records in MySQL and generated queries for business insights
  -  i.e. revenue from premium subscriptions, most popular user characteristcs, whether Bumble's dating events helped users match
  -  ERD:
  <img src="https://raw.githubusercontent.com/JuniperZhuDiwei/MySQL-dbms/main/group-Bumble-db-creating-queries/Bumble_ERD.png" width="600" height="380">

  

---
## [3. AI and Deep Learning Projects (Python)](https://github.com/JuniperZhuDiwei/AI-Deep-Learning)
[3.1. Wine category classification with Keras Functional API](https://github.com/JuniperZhuDiwei/AI-Deep-Learning/blob/main/1.%20Wine%20classification_Keras%20functional%20API.ipynb)


---
## [4. Text Analysis and Social Network Analysis Projects (Python)](https://github.com/JuniperZhuDiwei/Text-SocialNetwork-analysis)
### [4.1. Edmund car forum user generated contents analysis](https://github.com/JuniperZhuDiwei/Text-SocialNetwork-analysis/tree/main/CarForum-UGC-analysis)
- **Keywords: ntlk, lift ratio, MDS plot, sentiment analysis**
- Group project (6 members)
- With nltk package, analyzed mentions of top 10 popular car brands and car attributes based on UGC scraped from a forum. We calculated lift ratios of pairs of car brands and attributes, drew MDS plots for clustering, and did sentiment analysis. 
  - MDS plot of brands showing which brands are frequently compared by users:

  <img src="https://drive.google.com/uc?export=view&id=1iCWB66R8-WzRlO-hWLfkjVF7OAf34N1z" width="350" height="250">
- Identified BMW as the aspirational brand to the users, since it has the highest number of mentions, strong association with purchase attributes and is less compared with other brands.


### [4.2. User generated contents analysis of 9 airlines](https://github.com/JuniperZhuDiwei/Text-SocialNetwork-analysis/tree/main/Airlines_UGC_analysis)
- **Keywords: ntlk, lift ratio, MDS plot, sentiment analysis, topic modeling**
- Group project (6 members)
- Analyzed 9 airlines and onboard experience attributes based on UGC scraped from forums. Calculated lift scores, drew MDS plots, did sentiment analysis and topic modeling. 
  - [Interactive Power BI dashboard of sentiment scores with respect to airlines and attributes:](https://github.com/JuniperZhuDiwei/PowerBI-Dashboarding)

  <img src="https://drive.google.com/uc?export=view&id=1VlWiDedNqp-4H8s2j_0OSDqttLYu7uCw" width="650" height="400">
- Based on sentiment analysis results, provided recommendation to passengers in terms of different onboard experience needs; provided advice to airlines about attributes to improve.

### [4.3. Text classification of high/low salaries based on job descriptions](https://github.com/JuniperZhuDiwei/Text-SocialNetwork-analysis/tree/main/Salaries-jd-text-classification)
- **Keywords: nltk text classification, Naïve Bayes classifier**
- Built a text classification model for labeling salary level by job descriptions and generate a list of most informative features.
  - i.e. appearing of “off shore”, “architecture”, “unix” indicates a high salary
  - i.e. appearing of “school”, “friday”, “enjoy” indicates a low salary


---
## [5. Data Modelling with R](https://github.com/JuniperZhuDiwei/R-projects)
### [5.1. IMDb rating prediction](https://github.com/JuniperZhuDiwei/R-projects/tree/main/IMBb-rating-prediction)
- **Keywords: Recursive Feature Elimination, Polynomial regression model, Spline model**
- Group project (6 members)
- Built polynomial regression model (after comparing to spline model) that passed heteroskedasticity test to predict IMDb ratings of movies with selected features. 

### [5.2. Identifying most-in-need countries by socio-economic and health factors](https://github.com/JuniperZhuDiwei/R-projects/tree/main/life-exp-PCA-tree-clustering)
- **Keywords: Tree-based classification model, PCA, Clustering**
- With selected socio-economic factors (GDP per capita and income per capita), and health factors (fertility rate and spending on healthcare), generated random forest classification model and clusters (with PCA) to identify countries that are eligible for international help.
  -  Identified countries to receive help: Democratic Republic of the Congo, Liberia, Burundi, Niger, Central African Republic
  -  PCA:

  <img src="https://drive.google.com/uc?export=view&id=15KdF_A8pBzk-nOwTwJYj3ZPWTPBhdqop" width="350" height="300">


