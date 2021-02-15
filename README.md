# Heart-Disease-ML-Classification
Data Analytics Club sponsored ML classification project - Feb 2021


The goal of this project is to use machine learning to predict the presence or absence of heart disease.

Dataset Heart.csv was downloaded from Kaggle https://www.kaggle.com/ronitf/heart-disease-uci, while the original dataset came from the UCI webiste https://archive.ics.uci.edu/ml/datasets/Heart+Disease. The dataset initially had 76 variables, however the data was manipulated and only 14 variables were kept for the purpose of this project. 

Attribute information as provided by Kaggle website

0-age; 
1-sex; 
2-cp - chest pain type (4 values); 
3-trestbps - resting blood pressure; 
4-chol - serum cholestoral in mg/dl; 
5-fbs - fasting blood sugar > 120 mg/dl (1=true, 0=false); 
6-restecg - resting electrocardiographic results (values 0,1,2); 
7-thalach - maximum heart rate achieved on the thallium stress test; 
8-exang - exercise induced angina (1=yes, 0=no); 
9-oldpeak - ST depression induced by exercise relative to rest; 
10-slope - the slope of the peak exercise ST segment (values 0,1,2); 
11-ca - number of major vessels (0-3) colored by flourosopy; 
12-thal - 3 = normal; 6 = fixed defect; 7 = reversable defect; 

From the above predictor variables we need to come up with a model that accurately predicts whether a subject has heart disease on admission or not
We can then compare the predictions from the model to the target values given in the dataset
13-target - 0=heart disease not present; 1=heart disease present;

The original dataset was split into training and testing datsets at the ratio 70:30 using the random method with a fixed seed for reproducability
