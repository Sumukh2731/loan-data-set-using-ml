# loan-data-set-using-ml
Loan Approval Prediction
Subtitle: Predicting Loan Approval Status using Machine Learning Models
Your Name
Date

2: Objective
Aim:
To develop a predictive model to accurately predict loan approval status based on features
like credit score, annual income, loan amount, etc.

 3: Libraries and Dataset
Libraries Used:
 NumPy
 Pandas
 Matplotlib
 Seaborn
 Scikit-Learn
 XGBoost
Dataset:
Loaded from loan_approval_dataset.csv

 4: Feature Description
Columns in Dataset:
 loan_id: Unique ID (Dropped)
 no_of_dependents
 education: Graduate/Not Graduate
 self_employed: Employment Status
 income_annum
 loan_amount
 loan_term
 cibil_score: Credit Score
 residential_assets_value
 commercial_assets_value
 luxury_assets_value

 bank_asset_value
 loan_status: Approved/Rejected

 5: Feature Engineering
 Dropped: loan_id
 Created New Features:
o Movable_assets
o Immovable_assets
 Dropped Columns: bank_asset_value, luxury_assets_value,
residential_assets_value, commercial_assets_value

 6: Exploratory Data Analysis (EDA)
 No Missing Values
 Total Entries: 4269
 Total Features: 10

 7: Visualizations
 Number of Dependents Distribution
 Number of Dependents vs Loan Status

Slide 8: Education vs Loan Status
 Observation: Minimal difference in loan approval rates between graduates and non-
graduates

 9: Loan Amount and Term Analysis
 Loan Amount vs Loan Term
 Loan Amount &amp; Term vs Loan Status

 10: CIBIL Score Analysis
 CIBIL Score Distribution
 CIBIL Score vs Loan Status

11: Data Preprocessing
 Label Encoding:
o education
o self_employed
o loan_status
 Feature Scaling: Not applied (optional)

12: Correlation Analysis
 Heatmap of Correlation Values

 13: Model Evaluation
 Models Tested:
o Logistic Regression
o Support Vector Classification (SVC)
o Decision Tree Classifier
o Random Forest Classifier
o AdaBoost Classifier
o Gradient Boosting Classifier
o XGBoost Classifier

14: Model Performance
 Decision Tree: 98% Accuracy
 Random Forest: 98% Accuracy
 Gradient Boosting: 98.82% Accuracy
 XGBoost: 98.71% Accuracy
 15: Conclusion
 Best Performing Models:
o Decision Tree with Hyperparameter Tuning
o Gradient Boosting
o XGBoost
 Key Insights:
o Decision Tree and Boosting Classifiers show excellent performance.
o SVM and Logistic Regression performed less effectively.
