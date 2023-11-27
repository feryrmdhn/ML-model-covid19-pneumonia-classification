# Covid-19 pneumonia classification

## Project Overview

This project involves the implementation of a classification model using various machine learning algorithms to predict a target variable. 
The dataset is loaded, preprocessed, and used to train different classification models. 
The evaluation of the models is conducted using metrics such as confusion matrix, learning curves, and other relevant performance indicators.
## Overall Steps:
1. Import all Libraries & Load the Dataset </br>
   Import necessary libraries for data manipulation, visualization, and machine learning. </br>
   Load the dataset for analysis. </br>

2. Split Data (Train and Test) </br>
   Divide the dataset into training and testing sets for model training and evaluation.

3. Exploratory Data Analysis (EDA) </br>
   Analyze categorical and numerical data for insights into the dataset.

4. Removing Redundant Variables </br>
   Identify and remove redundant variables based on business value.

5. Data Preparation: Data Train </br>
    Drop duplicated data. </br>
    Analyze and handle outliers. </br>
    Handle missing values. </br>

6. Data Preparation: Data Test </br>
  Drop duplicated data.</br>
  Analyze and handle outliers.</br>
  Handle missing values.</br>

7. Split Data into Xtrain, ytrain, Xtest, ytest </br>
   Separate features (X) and target variable (y) for both training and testing sets.

8. Encoding Preparation </br>
        Prepare the data for encoding.

9. Encode Separately for Data Train and Data Test </br>
        Perform encoding on categorical variables for both training and testing sets.

10. Split Xtrain and Xtest into Different Categories </br>
    Split the features into different categories.

11. Standard Scaler </br>
    Standardize the features using Standard Scaler.

12. Modelling Classification ML Algorithms: </br>
    Logistic Regression</br>
    K-Nearest Neighbor (KNN)</br>
    Naive Bayes </br>
    Support Vector Machine (SVM) </br>

13. Evaluation Model: </br>
    Confusion Matrix Evaluation </br>
    Learning curve Regression </br>
    Learning curve K-Nearest Neighbor (KNN) </br>
    Learning curve Naive Bayes </br>
    Learning curve Support Vector Machine (SVM) </br>

## Requirements :
pandas: 1.5.3 </br>
numpy: 1.23.5 </br>
matplotlib: 3.7.1 </br>
seaborn: 0.12.2 </br>
plotly: 5.15.0 </br>
scipy: 1.11.1 </br>
scikit-learn: 1.2.2 </br>

#Tags </br>
covid19, classification, machine learning, health, pneumonia

Kaggle: https://www.kaggle.com/code/feryramadhanc/covid-19-penumonia-classication
