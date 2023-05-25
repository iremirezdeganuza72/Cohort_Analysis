## PREDICTION MODELS & CLUSTERING - TRAVEL INDUSTRY :hotel:
                                

##  Index

- [Description](#Description)
- [How did I carry out the project?](#How-did-I-carry-out-the-project)
- [Implementation of project](#Implementation-of-project)
- [Dataset](#Dataset)
- [Objectives](#Objectives)
- [Author](#Author)

##  Description

"PREDICTION MODELS & CLUSTERING - TRAVEL INDUSTRY" is a project carried out for the travel industry in which through a dataset of customers of a hotel that includes three years, and after data processing, several machine learning models are applied to find out which of them is the best predictor. Subsequently, the KMeans algorithm is used to detect the most appropriate number of cohorts for this dataset, as well as the metrics that identify it.  Python and several libraries such as pandas, matplotlib, seaborn, sklearn,... are used.

![cluster](raw.githubusercontent.com/iremirezdeganuza72/Cohort_Analysis/main/pictures/cluster.png)


![cluster](wsl.localhost/Ubuntu-18.04/home/iremirezdeganuza/Cohort_Analysis/pictures/cluster.png)




## How did I carry out the project?

I donwload the customer dataset from Kaggle with 31 variables describing a total of 83,590 instances (customers). It comprehends three full years of customer behavioral data. In addition to personal and behavioral information, the dataset also contains demographic and geographical information

After analizying the information containing the dataset, I prepared data (reviewing nulls, applying onehotencoding, reducing the number of source markets,...) to apply the different algorithms of Machine Learning (ML) such as; KNN, SVC, Random Forest,... to verify which of them was the best predictor with the relation between customer and roomnights booked. 

On the other hand, I have verified the quality of predictions with several metrics (f1, accuracy, recall, precision,...)

Finaly, my objective was to calculate the different clusters that compose the customers, for that,  I used the K-Means algorithm.The k-means algorithm is a clustering method that divides a data set into k groups or clusters. Silhouette coefficient or Silhouette score is the  metric used to evaluate the quality of clusters created by the algorithm.

One of the objectives was to see the correlation between serveral variables and the three clusters created.

## Dataset

I worked with a Kaggle dataset (https://www.kaggle.com/datasets/nantonio/a-hotels-customers-dataset) with 31 variables describing a total of 83,590 instances (customers). It comprehends three full years of customer behavioral data. In addition to personal and behavioral information, the dataset also contains demographic and geographical information.

## Objectives

Main objectives achieved:

1. Creation of trained model with a high level of prediction for relationship between Customer and roomnights booked.
2. Creation  customer clusters' according to the data.
3. Analysis of prediction models and customers' clusters through several metrics.
4. Check the correlation of several variables that make up the dataset.

## Authors

This project was made by Iñigo Remirez de Ganuza;
