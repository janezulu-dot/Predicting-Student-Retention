University of Dallas, Irving, TX
Author: Jane Zulu

Introduction:
This project focuses on analyzing and predicting student dropout rates and academic success in higher education institutions. The dataset includes student demographics, socio-economic status, and academic performance data sourced from Kaggle.

Project Objectives:
Data Analysis and Visualization: Explore the dataset to understand key features and visualize trends.
Feature Selection and Engineering: Identify relevant features and perform feature engineering to improve model accuracy.
Modeling and Prediction: Apply machine learning algorithms to predict student outcomes and evaluate model performance.
Interpretation and Insights: Provide actionable insights for improving student retention strategies.
Installation and Setup
To run this project, you'll need Python 3.x and the following libraries: Pandas, Matplotlib, Seaborn, Scikit-learn, Statsmodels, XGBoost, Plotly, Yellowbrick, and Prince.

Data Exploration and Cleaning:
Cleaning: Removed records with the outcome "Enrolled" and renamed columns for consistency.
EDA: Analyzed student demographics, socio-economic status, and academic performance.
Visualizations: Created plots for the distribution of student outcomes and age at enrollment.

Modeling Techniques:
Three primary models were used:
Logistic Regression: Baseline model for binary classification.
K-Nearest Neighbors (KNN): Captures complex, non-linear relationships.
XGBoost: Powerful ensemble learning for higher accuracy.

Model Evaluation:
Models were evaluated using accuracy, precision, recall, confusion matrix, and ROC curves.

Model Performance Summary:
Model	Training Accuracy	Testing Accuracy
Logistic Regression	91%	90%
K-Nearest Neighbors	91%	89%
XGBoost	95%	89%

Conclusion:
Key Predictors: Age and academic performance significantly affect student outcomes.
Socio-Economic Impact: These factors play a role but need deeper analysis.
Model Insights: XGBoost performed best but requires careful tuning.

Future Work:
Explore additional features and advanced models.
Conduct longitudinal analysis for dynamic predictions.
