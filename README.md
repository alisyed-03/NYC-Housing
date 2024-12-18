# Housing Quality Prediction and Clustering in New York City Housing

## Project Overview
This project was developed as part of CS105: Data Analysis Methods, at University of California, Riverside. This project aims to predict housing deficiencies (e.g., leaks, mold, heating issues) in New York City residential units based on building characteristics and household demographics. We utilized a combination of supervised learning (classification models) and unsupervised learning (clustering methods) to identify systematic issues and patterns within the dataset. The project provides actionable insights to prioritize maintenance efforts and improve housing quality.

## Objectives
- Predict Housing Deficiencies: Build a classification model to predict the likelihood of housing deficiencies using features like building age, income, and household size.
- Identify Patterns in Deficiencies: Use clustering techniques to uncover systematic issues (e.g., common deficiencies, building types) that contribute to poor housing conditions.
### Hypothesis Testing:
- Hypothesis 1: Older buildings and low-income households are more likely to experience deficiencies.
- Hypothesis 2: Clusters of deficiencies reveal underlying systematic issues.
- Hypothesis 3: Household income is the most significant factor associated with deficiencies.

## Data Source
The dataset includes detailed records of NYC housing features, building conditions, and household demographics:

Deficiency Indicators: LEAKS, MOLD, NOHEAT, ELEVATOR_BROK, etc.
Building Characteristics: BUILDING_AGE, HHFIRSTMOVEIN
Demographic Data: TOTAL_INC_REC_P (Household Income), HHPOVERTY (Poverty Indicator)

## Machine Learning Methods
### Supervised Learning:
- Model Used: Random Forest Classifier
- Outcome: Achieved high predictive performance with an ROC-AUC score of 0.996.
- Key Finding: BUILDING_AGE emerged as the most critical factor influencing deficiencies, contributing ~80% of the model's feature importance.

### Unsupervised Learning:
- K-Means Clustering: Grouped housing units into clusters based on shared deficiencies.
- Hierarchical Clustering: Visualized systematic patterns using dendrograms.
- Key Insight: Clusters with severe deficiencies revealed widespread structural and heating issues.

This repository includes the dataset, analysis code, visualizations, and a powerpoint presentation created as part of the study.

Team Members: Ali Syed, William Dang, Javier Vargas, Sarah Pun, Arsenii Vasilev

