# Predict Customer Personality To Boost Marketing Campaign

## Introduction

In today's competitive business landscape, understanding customer behavior is paramount for the success of any marketing campaign. By gaining insights into the unique personality traits and preferences of customers, companies can tailor their marketing strategies to effectively engage with their target audience and boost conversion rates.

## Load Dataset

The dataset comprises 2240 records and 29 features, including numerical and categorical data types.

## Data Cleaning

After handling missing values, which were found in the `Income` feature with 24 missing values imputed using median values, and removing 203 outlier data (9%) from the dataset, the dataset was prepared for further analysis.

## Feature Engineering

Feature engineering involved identifying and addressing features with low correlation and high variance inflation factor (VIF) to enhance model performance. Seven features with low correlation, below 10%, with the response were dropped, while four features with high VIF were removed.

## Exploratory Data Analysis

Exploratory Data Analysis revealed insights into customer profiles, campaign performance, and relationships between variables. Key insights include:
- Average age around 54 years old.
- Average income around 50 million with significant variation.
- Majority have at least 1 child or teenager at home.
- Active customers make around 14 transactions on average.
- Average conversion rate is 3.8%.

## Data Preprocessing

Data preprocessing steps included addressing skewness and reducing dimensionality using Principal Component Analysis (PCA). PCA reduced feature dimensions from 35 to 15.

## Modeling

Modeling techniques were employed to cluster customers based on their behavior and characteristics. The silhouette score indicated the optimal number of clusters to be 2.

## Evaluation

Evaluation of the clustering model led to the identification of distinct customer segments.

## Business Recommendation

Based on the clustering results, tailored business recommendations were provided for each customer segment.
