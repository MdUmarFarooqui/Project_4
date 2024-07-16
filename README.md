# Mobile Phone Price Prediction with Feature Extraction
This project aims to develop a machine learning model for predicting mobile phone prices based on key features.

By understanding the features that most influence price, we can assist a prominent mobile phone seller in refining their pricing strategy.

# Project Goals:
Build a predictive model to estimate mobile phone prices.

Identify the most influential features affecting price through feature extraction.

Recommend impactful features for informed pricing and marketing decisions.

# Data:
The provided dataset contains detailed information on various mobile phones, including:

Model, Color, Memory, RAM, Battery Capacity, Rear/Front Camera Specs, AI Lens Presence, Mobile Height, Processor and Price (target variable)

# Methodology:
Data Exploration:
Analyze dataset structure, data types, and feature value ranges.

# Data Preprocessing:
Handle missing values, outliers, and inconsistencies.

Encode categorical variables (e.g., one-hot encoding).

# Feature Extraction:
Identify highly impactful features using:

Statistical methods (correlation analysis)

Feature importance techniques (selection or dimensionality reduction)

# Model Building:
Split the dataset into training and testing sets.

Develop a machine learning model for price prediction (using linear regression, random forests).

# Model Evaluation:
Assess model performance using metrics like mean absolute error (MAE) and root mean squared error (RMSE).

# Feature Importance Analysis:
Validate feature importance identified during extraction using model insights.

# Reporting & Visualization:
Comprehensive report with visualizations summarizing key findings are derived to show the client.

# Tools and Libraries:
This project involves employing:

Machine learning libraries (Scikit-learn, TensorFlow, etc.)
Data visualization tools (Matplotlib, Seaborn)
Data analysis techniques (correlation, feature selection)
Repository Structure
Mobile Data.csv/: Contains the dataset used for analysis.
Feature_Extraction and price prediction of mobiles.ipynb/: Jupyter notebooks for each stage of the analysis.
Final_mobile_data.csv/: Data after cleaning and featuring engineering

# Conclusion:
This project successfully developed a machine learning model for predicting mobile phone prices based on key features. Through feature extraction techniques, we identified the most influential factors impacting price, providing valuable insights for informed decision-making.
