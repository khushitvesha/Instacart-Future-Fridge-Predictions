# Future Fridge with Instacart: Precision Grocery Predictions

## Overview
This project leverages data-driven insights to enhance the online grocery shopping experience through personalized product recommendations and optimized inventory management, utilizing machine learning and advanced analytics.

### Team Members:
- Aishwarya Jayant Rauthan
- Khushi Khushi
- Saachi Dholakia
- Tiancheng Yang
- Xinyuan Hu

## Contents
1. [Executive Summary](#executive-summary)
2. [Data Preparation](#data-preparation)
3. [Problem Statement](#problem-statement)
4. [Methodologies](#methodologies)
5. [Challenges](#challenges)
6. [Business Relevance](#business-relevance)
7. [Future Work](#future-work)
8. [Contributions](#contributions)
9. [Results](#results)

## Executive Summary
The aim of this project is to predict which previously purchased products will appear in a user's next order, based on their historical data. This will potentially increase customer satisfaction and loyalty by providing personalized recommendations and improving the overall shopping experience.

## Data Preparation
- **Database Size:** 324,345 rows, 15 columns sampled from 30+ million records.
- **Sampling:** Data reduced to 1% for manageability.
- **Normalization:** Standard Scaler used for standardization of numerical columns.

## Problem Statement
Enhance the shopping experience by predicting user preferences and suggesting relevant products, thereby improving customer satisfaction and loyalty.

## Methodologies
- **Exploratory Data Analysis (EDA):** Analyzed order distributions, reorder frequencies, and department popularity.
- **Market Basket Analysis:** Employed to identify strong product associations.
- **K-means Clustering:** Used for customer segmentation.
- **Dimensionality Reduction:** Applied PCA and t-SNE for better visualization and interpretation of data.
- **Hierarchical Clustering:** Utilized for deeper insights into customer grouping.

## Challenges
- **Large Data:** Required extensive sampling due to computational limits, leading to potential loss of subtle patterns.
- **Market Basket Analysis:** Computational challenges faced with extensive product combinations.
- **Dimensionality Reduction:** Techniques like t-SNE and Hierarchical clustering required resampling for feasibility.

## Business Relevance
This analysis allows for:
- **Personalized Marketing Campaigns:** Better customer targeting through detailed segmentation.
- **Optimization of Inventory and Sales:** Ensuring availability of high-demand products.
- **Improved User Experience:** Through relevant product suggestions.

## Future Work
- **Model Updates:** Continuously refine and update the model with new data.
- **Cost Efficiency:** Improve cost efficiency by optimizing stock levels and operations.
- **Data Privacy and Ethics:** Ensure ethical use of data and maintain user privacy.

## Contributions
- **Aishwarya Jayant Rauthan:** Data cleaning, Market Basket Analysis.
- **Khushi Khushi:** Hierarchical Clustering, Market Basket Analysis, PCA.
- **Saachi Dholakia:** EDA, PCA.
- **Tiancheng Yang:** EDA, K-means Clustering.
- **Xinyuan Hu:** EDA, K-means Clustering.

## Results
Achieved enhanced customer experience and increased sales through effective segmentation and personalized recommendations. Practical applications have shown significant potential in optimizing grocery retail operations.
