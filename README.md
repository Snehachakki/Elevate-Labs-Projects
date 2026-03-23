Overview
This repository contains 7 data science projects covering various domains including customer analytics, entertainment, HR, hospitality, transportation, social media, and healthcare.

Projects List
1. Customer Lifetime Value (CLV) Prediction
Goal: Predict long-term customer revenue value using transaction data.
Methods: Feature engineering (RFM), Linear Regression, Random Forest
Key Finding: Frequency and monetary value are strongest predictors

2. Movie Success Prediction & Sentiment Analysis
Goal: Predict box office gross and analyze sentiment in movie reviews.
Methods: VADER sentiment analysis, Linear Regression
Key Finding: R² score of 0.42; ratings and votes significantly impact success

3. HR Analytics: Employee Attrition Prediction
Goal: Predict employee turnover and identify key drivers.
Methods: Logistic Regression, EDA with Seaborn
Key Finding: 88.77% accuracy; compensation, job satisfaction, and early tenure are critical factors

4. Airbnb Dynamic Pricing Recommendation
Goal: Predict optimal listing prices based on property attributes.
Methods: Linear Regression, one-hot encoding, feature scaling
Key Finding: MAE of $42.42; location and availability are top price drivers

5. EV Charging Demand Forecasting
Goal: Forecast daily user demand at EV charging stations.
Methods: Linear Regression, feature importance analysis
Key Finding: R² of 0.85-0.90; capacity and location are strongest predictors

6. YouTube Trending Video Analytics
Goal: Identify patterns in trending videos across countries.
Methods: Sentiment analysis, EDA, cross-country comparison
Key Finding: Negative sentiment titles get 31% more views; US videos average 2.36M views

7. Healthcare No-Show Prediction
Goal: Predict patient appointment no-shows and identify risk factors.
Methods: Decision Tree Classifier, feature engineering
Key Finding: 79.74% accuracy; waiting days is the strongest predictor (75% importance)

Technologies Used
Category	Tools
Programming	Python
Data Processing	Pandas, NumPy
Machine Learning	Scikit-learn (Linear Regression, Logistic Regression, Decision Tree, Random Forest)
Natural Language Processing	VADER, TextBlob
Visualization	Matplotlib, Seaborn, Power BI
Data Analysis	EDA, Feature Engineering, Correlation Analysis

Key Takeaways
Feature engineering significantly improves model performance
Domain knowledge helps in selecting and interpreting features
Ensemble methods often outperform simple linear models
Class imbalance is a common challenge requiring special handling
