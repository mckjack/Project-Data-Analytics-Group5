# Project-Data-Analytics-Group5

### SEGMENT 2
Our draft Google slide presentation: https://docs.google.com/presentation/d/1aUmmhFLKrxk1ZIevb6XBO8-0x8Yc5DKfiZdjPkO4udA/edit?usp=sharing

## 1. Create database in RDS/MongoDB (or a database of your choice) along with tables from the ERD and the data imported in the tables.


## 2. Python code connecting to the database and getting bringing data back in Python.


## 3. Python/R/Tableau to perform Exploratory Data Analysis (understanding the data and the relationship within the data)


## 4. Python code for training and testing the benchmark (simple) machine learning model as per your Segment 1 deliverable e.g. Logistic Regression for classification, Kmean for clustering etc.



### SEGMENT 1

## 1. Database Mock Up (Preferably a ERD - Entity Relationship Diagram)
![image](https://user-images.githubusercontent.com/100737452/179638294-800abcb7-d0b4-4ac2-82b5-e4c165a400d9.png)


## 2. Github repo and everyone has merged with the main branch at least once
Everyone in our project team has merged to the main branch: ![image](https://user-images.githubusercontent.com/100737452/179632030-62c03404-f0aa-421b-b06b-240559ba574a.png)

## 3. Proposed findings and a hypothesis of results (i.e. business problem contextualized with data driven results)
Using the following datasets...
1. Crude oil prices
2. Electric car sales

Questions we hope to answer in our project are:
1. Did rising/falling gas prices have any effect on electric car sales in the US? 
2. Did answer to #1 vary significantly from different states?
3. Can we predict electric car sales over the next year based on the 2 datasets?
4. Can we predict crude oil prices over the next year?

We selected this topic due to rising gas prices and we wanted to study how it impacts consumer purchases for automobiles.  Our hypothesis is that the gas prices do impact consumer choices.

## 4. Diagram of Data Pipeline (ETL, Database, and Machine Learning model)
![image](https://user-images.githubusercontent.com/100737452/179631920-3db32829-3576-46e6-b218-e2d0657f6d25.png)
- We decided based upon our hypothesis and dataset variables that a time-series regression model would be the most ideal model going forward. From the generated database we will use this model to predict the total number of electric cars sold in a given time frame. 
