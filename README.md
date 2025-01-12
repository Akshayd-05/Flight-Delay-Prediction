Harnessing Machine Learning for Flight Status Prediction
Project Overview
This project leverages machine learning techniques to predict flight delays using a comprehensive dataset spanning 2019 to 2023. The aim is to provide actionable insights for airlines and passengers, improving operational efficiency and decision-making.

Dataset
Source: Airline and government records.
Size: 3 million entries.
Features: Detailed flight information, including schedules, delays, distances, and airline-specific details.
Objectives
Develop predictive models for classifying flight status as either delayed or on time.
Identify significant predictors influencing flight delays.
Enhance decision-making in airline operations and customer communication.
Models Implemented
Logistic Regression

Accuracy: ~99.999%.
Key Predictor: Departure delay (DEP_DELAY).
Achieved perfect precision and recall.
XGBoost

Accuracy: ~99.11%.
Focuses on operational factors such as departure and taxi times.
Handles large datasets efficiently.
Key Findings
Departure delay and taxi-out time are the most influential predictors of flight delays.
Temporal and distance-based features have minimal impact on delay predictions.
Both models offer robust performance, with logistic regression excelling in interpretability and XGBoost in handling complex patterns.
Tools and Libraries
Programming Language: Python
Libraries:
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Modeling: Scikit-learn, XGBoost, Statsmodels
