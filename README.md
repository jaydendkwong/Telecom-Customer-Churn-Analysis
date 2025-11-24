# Telecom Customer Churn Analysis
## Overview
This project was completed as part of my ECN 142 (Economics & Business Data Analytics) course at UC Davis. The goal was to explore customer churn in the telecom industry by applying various econometric modeling and variable selection techniques to a real-world dataset.

## Objective
The main objective was to build predictive models to understand which customer behaviors and characteristics most strongly influence churn, and to evaluate the effectiveness of different variable selection and model-building techniques.


## Methodology
- **Exploratory Data Analysis** using boxplots and correlation matrices
- **Logistic Regression** (baseline and polynomial terms)
- **Variable Selection Techniques**:
  - Best Subset Selection
  - Forward Stepwise Selection
  - LASSO Regularization
- **Model Comparison** based on accuracy
- **Multicollinearity Check** using correlation plots
- **PCA (Principal Component Analysis)** for dimensionality reduction
- **Classification Tree** modeling with pruning and accuracy evaluation

## Key Results
- The final LASSO + stepwise logistic regression model achieved an accuracy of **86.3%**
- The **classification tree** model produced a higher accuracy of **92.5%**, with high sensitivity and good balanced accuracy
- Important churn predictors included:  
  `ContractRenewal`, `DataPlan`, `CustServCalls`, `DayMins`, `OverageFee`, and `RoamMins`

## Tools & Packages
- **Language**: R  
- **Key Libraries**: `glmnet`, `leaps`, `caret`, `corrplot`, `rpart`, `ggplot2`

## Reflections
This project deepened my understanding of predictive modeling, feature selection, and model evaluation in an applied context. It also strengthened my skills in R for statistical computing and data visualization.
