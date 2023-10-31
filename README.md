# Data-analysis

## Overview

This project involves the analysis of data for 71,279 policyholders of an automobile insurance company for the years 2009 and 2010. 
The dataset includes information about whether or not these policyholders experienced at least one at-fault accident during the calendar 
year (indicated by the binary variable "Surv1"), along with various other variables (refer to the variable dictionary in the appendix).

The primary objective of this analysis is to create a segmentation rule for this portfolio of policyholders, distinguishing those at higher 
risk from those at lower risk. The analysis utilized both the Random Forest and Logistic Regression methods to achieve this goal.

## Project Steps

1. **Data Collection and Preparation**:
   - Gathering data on 71,279 policyholders, ensuring the dataset is clean and properly formatted.
2. **Exploratory Data Analysis (EDA)**:
   - Conducting an initial exploration of the data to understand the distributions, relationships, and characteristics of the variables.
3. **Feature Selection and Engineering**:
   - Identifying relevant features (variables) that might influence the risk of an at-fault accident.
4. **Model Building**:
   - Utilizing two different modeling techniques: Random Forest and Logistic Regression,Building models on a training dataset to predict policyholders' risk.
5. **Cross-Validation**:
   - Employing cross-validation to evaluate the models' performance on an independent test dataset.
7. **Segmentation Rule**:
   - Creating a rule for segmenting policyholders into risk and non-risk categories based on model predictions.
     
