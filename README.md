# Credit-Risk-Prediction
The objective of this project is to build a machine learning model that predicts whether a loan applicant is likely to default or not. The goal is to analyze financial and demographic attributes of applicants and develop a data-driven solution that supports credit risk assessment and informed lending decisions.

# Approach

The project follows a structured end-to-end machine learning workflow:

# Data Understanding & Exploration

Loaded and inspected the loan dataset.

Analyzed dataset structure, feature types, and summary statistics.

Performed exploratory data analysis (EDA) to identify patterns and relationships between variables.

# Data Preprocessing

Handled missing values using appropriate statistical methods (mode for categorical variables and median for numerical variables).

Encoded categorical features using Label Encoding.

Separated input features and target variable.

Split the dataset into training and testing sets.

# Model Development

Trained classification models including Logistic Regression and Decision Tree.

Evaluated model performance on unseen test data.

# Model Evaluation

Measured accuracy to assess overall prediction performance.

Analyzed the confusion matrix to evaluate classification errors.

Reviewed precision, recall, and F1-score for deeper performance insights.

# Results & Insights

The model successfully identified patterns in applicant financial and demographic data.

Features such as credit history, income level, and loan amount showed strong influence on default prediction.

Proper handling of missing values and categorical encoding significantly improved model performance.

Logistic Regression provided stable baseline performance, while Decision Tree captured non-linear relationships.

# Conclusion

This project demonstrates a complete machine learning workflow for credit risk prediction. By applying structured preprocessing, feature engineering, and model evaluation techniques, the system provides meaningful insights into loan default risk. The results highlight the importance of data quality and feature selection in building reliable financial risk models.

# Future Improvements

Apply advanced algorithms such as Random Forest, XGBoost, or Gradient Boosting.

Perform hyperparameter tuning and cross-validation for improved generalization.

Address potential class imbalance using resampling techniques.

Conduct feature importance analysis for deeper interpretability.

Deploy the model as an API or web application for real-world usage.

# Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook
