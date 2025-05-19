# fraudulent-claim-detection
Problem Statement: - Global Insure (an insurance company) processes thousands of claims annually, with a significant percentage being fraudulent, leading to financial losses. The current manual fraud detection process is inefficient, often detecting fraud too late. The company seeks to improve fraud detection by using data-driven insights to classify claims as fraudulent or legitimate early in the approval process, minimizing financial losses and optimizing claims handling.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
  ### Business Objective: 
  Build a model that will classify claims as either fraudulent or legitimate based on historical claims and customer details. This model should help the organization to predict which claims are likely to be fraudulent before they are approved.

  ### Approach:
  The CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology was followed to build the model. The steps included:
  1.	**Data Preparation**: Processed and prepped the data for analysis.
  2.	**Data Cleaning**: Handled missing values and fixed datatypes.
  3.	**Data Splitting**: Divided the data into training and test sets.
  4.	**Exploratory Data Analysis (EDA)**: Conducted thorough analysis on the training data to understand patterns and distributions.
  5.	**Feature Engineering**: Created new features to improve model performance.
  6.	**Model Building**: Developed two models — Logistic Regression and Random Forest.
  7.	**Feature Selection**:
         - For Logistic Regression used RFECV.
         - For Random Forests used Feature Importance
  8.	**Model Fine-Tuning**:
         - Determined the optimal cutoff point for Logistic Regression.
         - Tuned hyperparameters using GridSearchCV to improve both models.
  9.	**Model Evaluation**: Assessed model performance using key metrics like Accuracy, Recall, Precision and F1-Score.


 ### Techniques:
 Specific tools or methods used at different steps of model building are mentioned below: 
 -	**Data preprocessing**: One-Hot encoding, Feature scaling through StandardScalar 
 -	**Model building**: Logistic Regression, Random Forests 
 -	**Model Optimization**: Accuracy, Specificity & Sensitivity Cutoff graph, GridSearchCV 
 -	**Evaluation metrics**: Accuracy, Confusion Matrix, Recall

## Conclusions
Here's an analysis of the performance of the Logistic Regression and Random Forest models, based on the evaluation metrics: Sensitivity, Specificity, Precision, Recall, F1-Score, and Accuracy.
![image](https://github.com/user-attachments/assets/eb07be41-06a3-420b-bdaf-0b31205e9ecd)

- In fraud detection to **maximize the detection of actual fraudulent cases (high recall)**, and considering that the **Logistic Regression model achieves a higher F1-Score (0.73)** and a substantially **higher Recall (0.90)**, the **Logistic Regression model would be suggested**. 

## Technologies Used
- **python** - 3.13.1
- **numpy** - 2.2.1
- **pandas** - 2.2.3
- **matplotlib** - 3.10.0
- **seaborn** - 0.13.2
- **statsmodels** - 0.14.4
- **sklearn** - 1.6.1

## Acknowledgements

- This project was inspired by Upgrad IIIT Bangalore PG program on ML and AI.
- This project was based on Multiple linear regression


## Contact
Created by @[GVChalamaReddy](https://github.com/GVChalamaReddy) & @[Utkarsh Sanwal](https://github.com/infinit-loop) - feel free to contact me!

