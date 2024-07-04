# Prediction and Dashboarding Solutions for Healthcare Employee Attrition

### Author: https://github.com/halepino

## Overview
A Power BI dashboard was created to examine relationships between employment variables and attrition (coded as yes 1/no 0). Recursive feature elimination (RFE) was conducted accross a range of N variables until an optimal amount was identified based on logistic regression scores on the test sample of employee data. Three models were then trained and compared for performance including a decision tree classifier, a gradient boosting classifier, and a mulit-layer preceptron (MLP) neural network. Following evaluation using classification reports, accuracy, and confusion matrices, the MLP model was found to have the best performance at 92% accuracy on test data.
## Repo Contents  
Code Files(ipynb)    
Power BI File (pbix)  
White Paper (pdf)  
Visual/Audio Presentation (pptx)      

## Dataset Features
The data for this project was sourced from kaggle.com, [here](https://www.kaggle.com/datasets/jpmiller/employee-attrition-for-healthcare?select=watson_healthcare_modified.csv). The dataset included 1676 rows of employee's data with 34 columns. A complete list of variables is shown below.
  
![image](https://github.com/halepino/HealthcareEmployeeAttrition_PredictiveAnalytics/assets/80646791/08bf4463-801d-41b9-9c85-a884088f7714)
