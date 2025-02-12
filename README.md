Predictive Modeling of Neighborhood Gentrification

Overview

This project predicts neighborhood gentrification using machine learning, leveraging Random Forest classification and key socioeconomic indicators. Developed for the Citadel Correlation-One Women’s Datathon, it provides insights for urban planners, policymakers, and investors.

Methodology

Datasets: Zillow Home Value Index (1996-2024), ACS 5-Year Estimates (2011-2023), Geographic Concordance Data.

Classification Criteria: Gentrification is identified based on rapid housing price appreciation, significant income growth, and education shifts.

Feature Selection: Recursive Feature Elimination with Cross-Validation (RFECV) identified five key indicators.

Model: Random Forest classifier with an 80%-20% train-test split.


Notes: Some of the intermediate data files a is too large to fit, to get them run gentrification_score.ipynb
