### Hi there 👋

# Lucas Ezequiel 

I´m a civil engineer switching to Data Science. I am focused on developing solutions to business problems using data, going from business context to deploying models and dashboards.

Since 2020, I have developed solutions for business problems such as identifying customers in churn, prioritizing customers for cross-selling, reducing CAC values, predicting store sales, and validating insights on rent values from data scraped from the web.

**Links:**
* [![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/lucas-medeiros-14a8a51a8/)
* [![Medium Badge](https://img.shields.io/badge/M-Medium-lightgrey)](https://medium.com/@lucas.medeiross)
* [![Twitter Badge](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2FLucasEz65097262)](https://twitter.com/LucasEz65097262)

The description of each project is detailed below.


### **Analytical Tools:**

**Data Collect and Storage:** web scraping, SQL, MySQL, DBeaver, Google BigQuery.

**Data Processing and Analysis:** Python, PySpark.

**Development:** Linux, Git. 

**Data Vizualization:** Power BI.

**Machine Learning Modeling:** Classification, Regression, Clustering. 

**Machine Learning Deployment:** Flask, Heroku.  


## Portfolio:

## [Insiders Clustering](https://github.com/LucasBMedeiros/insiders_clustering)


A UK-based online retail store has captured the sales data for different products for the period of one year (Nov 2016 to Dec 2017). The organization sells gifts primarily on the online platform. The customers who make a purchase consume directly for themselves. There are small businesses that buy in bulk and sell to other customers through the retail outlet channel. The company needs to find significant customers for the business who make high purchases of their favourite products, with the intent of rolling out a loyalty program to the high-value customers after identification of segments. Use the clustering methodology to segment customers into groups.

By performing feature engineering, data preparation, and dimensionality reduction, it is possible to evaluate a natural tendency of customers to cluster together. Moreover, I used Random Forest Regressor embedding as a way to represent a new feature space, before applying UMAP and t-SNE reduction on the data. The combination of a forest embedding and UMAP gave me the best results in clustering customers, giving a silhouette score of 0,67 for 8 cluster with the Hierarquical Clustering algorithm.

![](img/insiders/clusters01.png)
:--:
<b>UMAP space before and after Random Forest Embedding</b>

## [Sales Prediction](https://github.com/LucasBMedeiros/rossmann_sales)

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

![](img/rossmann/performance.png)
:--:
<b>XGBoostRegressor Sales Prediction error analysis</b>


## [User´s First Booking](https://github.com/LucasBMedeiros/airbnb_first_booking) 

Airbnb needs to predict which country a new user's first booking destination will be in this multilabel imbalanced classification problem. In the data there are 12 possible destination countries: 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF' (no destination found), and 'other'. By applying feature engineering, data preparation (rescaling and balancing), and feature selection, Random Forest Classifier can perform a Cohen Kappa´s score of 90.7% on the balanced dataset and 70.3% on the imbalanced dataset.

![](img/airbnb/random_bal.png)
:--:
<b>Confusion Matrix performance of Random Forest on Balanced Dataset</b>

## [Churn Prediciton](https://github.com/LucasBMedeiros/churn_prediction) 

In saturated markets, the cost to retain a customer is much less than prospecting for new customers. Machine Learning models are able to predict whether or not the customer will renew their service contract with the company in the next year. This information about the users is very important to optimize efforts in prioritizing customers who should continue with the contract in the company.
In this context, I developed a Machine Learning algorithm to identify whether or not a customer will stop using the banking service. The performance of the model in identifying the customer who will enter in churn period is 90%, which represents an additional U$ 20 million in revenue.


# Data Anaysis - Insight Projets

## [Web Scraping for EDA from rent prices at OLX](https://github.com/LucasBMedeiros/scraper_rent_prices)

Often, when looking to rent a place, advertising websites can be quite dispendious to scroll around. Looking to have a view of the big picture of prices for houses and apartments in a city, I developed this scraper that goes through OLX´s data, cleans it up and provides a basic EDA of house prices.

<!--
**LucasEzBM/LucasEzBM** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
