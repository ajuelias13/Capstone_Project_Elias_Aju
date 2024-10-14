# Income Level Prediction 

**Project Overview**

The aim of this project is to develop a machine learning model to predict whether a person’s income exceeds $50K per year based on census data. By leveraging various features from the census dataset, I will explore the data, engineer relevant features, build and evaluate a predictive model, and provide insights from the data. This project will help in understanding the factors that influence income levels and can assist in policy-making, socio-economic studies, and other related fields. 

**Dataset Overview**

The dataset used for this project consists of 48,842 entries, each representing an individual's census data. It contains the following 15 features:

1.	Age: The age of the individual.
2.	Workclass: The employment status of the individual (e.g., Private, Self-emp-not-inc, State-gov).
3.	Fnlwgt: The final weight, which represents the number of people the census believes the entry represents.
4.	Education: The highest level of education attained by the individual.
5.	Education-num: The number of years of education completed.
6.	Marital-status: The marital status of the individual (e.g., Never-married, Married-civ spouse).
7.	Occupation: The occupation of the individual (e.g., Adm-clerical, Exec-managerial).
8.	Relationship: The individual's relationship status within a family (e.g., Not-in-family, Husband).
9.	Race: The race of the individual (e.g., White, Black).
10.	Sex: The gender of the individual. 
11.	Capital-gain: Capital gains recorded for the individual.
12.	Capital-loss: Capital losses recorded for the individual. 
13.	Hours-per-week: The number of hours worked per week. 
14.	Native-country: The native country of the individual.
15.	Income: The target variable indicating whether the individual's income is greater than or less than or equal to $50K per year  (<=50K, >50K)

These features provide a comprehensive overview of the socio-economic status and work related characteristics of the individuals, which can be used to predict their income levels. By training a machine learning model on this dataset, I aim to accurately classify whether an individual's income exceeds $50K per year, thereby gaining insights into the determinants of income levels.

**Project outline**
1.	Data Collection and Preparation
a.	Data Importation
b.	Initial Data Inspection
2.	Exploratory Data Analysis (EDA)
3.	Data Preprocessing and Feature Engineering
a.	Handling Missing Values
b.	Encoding Categorical Variables
c.	Feature Scaling
4.	Model Development
a.	Train-Test Split
b.	Model Selection and Training
c.	Model Evaluation
