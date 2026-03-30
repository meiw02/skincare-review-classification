# Sephora Skincare Recommendation Analysis

## Overview
This project explores how product ratings and review characteristics influence whether skincare products are recommended and how these patterns relate to skincare categories and customer skin types.

## Dataset
This project uses the Sephora Products and Skincare Reviews dataset from Kaggle. The data includes product information and customer reviews scraped in March 2023, with records ranging from 2008 to 2022. It contains over 8,000 beauty products and about 1 million reviews on over 2,000 skincare products.

## Research Question
How do product ratings and review characteristics influence whether a skincare category will be recommended to customers with similar skin types?

## Methods
- Data cleaning and preprocessing in Python
- Feature selection including rating, recommendation status, price, and skin type
- Random Forest classification
- Exploration of class imbalance and baseline comparison

## Key Findings
The model struggled to outperform the baseline based on the most common class, suggesting that class imbalance affected performance. Some categories, such as sunscreen and face serum, were often confused, indicating overlap in product characteristics.

## Challenges
A major challenge was class imbalance, which caused the model to favor the most common category. Future improvements could include better feature engineering, text analysis from reviews, and balancing methods.

## Tools
Python, pandas, scikit-learn, matplotlib, Jupyter Notebook
