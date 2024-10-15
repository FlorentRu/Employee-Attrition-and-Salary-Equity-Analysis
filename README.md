# Class Project: Employee Attrition and Salary Equity Analysis

## Project Overview

This project focuses on analyzing employee demographic and employment-related data to address issues of class imbalance and demographic disparities, particularly in relation to employee attrition and salary/benefit equity. By employing advanced data processing techniques, the project enhances both the predictive power and fairness of machine learning models applied to this dataset. The ultimate goal is to ensure that the outcomes of these models are unbiased and equitable across different employee groups.

## Key Features
Class Imbalance Resolution (SMOTE): The dataset initially showed an imbalance in the target variable "quit," where fewer records represented employees who left the company. Using Synthetic Minority Over-sampling Technique (SMOTE), synthetic samples were generated for the underrepresented class, creating a more balanced dataset. This improved the model's ability to predict employee attrition accurately and reduced bias towards the majority class.

Bias Mitigation in Salary and Benefits: The dataset revealed salary and benefit disparities between male and female employees. Reweighting techniques were used to assign higher importance to underrepresented groups, such as female employees, in the analysis and modeling process. This approach corrected for the initial gender imbalance and ensured fair representation in salary and benefit-related outcomes.

## Objectives
Improve predictive accuracy for employee attrition by addressing class imbalance.
Mitigate gender-based biases in salary and benefits to promote equitable decision-making.
Enhance model fairness by reducing disparities in both predictive outcomes and salary distribution.

## Methodologies
SMOTE (Synthetic Minority Over-sampling Technique): Used to balance the "quit" variable by generating synthetic data points for the minority class (employees who quit).
Reweighting for Fairness: Applied to ensure equitable treatment of underrepresented groups in salary and benefit analysis, specifically addressing gender disparities.

## Results
Improved model performance for predicting employee attrition with a more balanced class distribution.
Reduced gender bias in salary and benefit predictions, leading to more equitable and fair analyses.
Recommendations
Continuously monitor for new biases and imbalances in the data.
Implement fairness-aware algorithms in future model developments.
Regularly audit models for fairness and ensure transparency in reporting methodologies.

## Conclusion
This project successfully applied data balancing and bias mitigation techniques to improve both the fairness and reliability of machine learning models related to employee attrition and salary equity. The techniques used can be extended to similar datasets and projects to promote fairer, data-driven decision-making.
