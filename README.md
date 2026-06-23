Data-Science-Projects


This repository contains my completed data science tasks including data exploration, visualization, and machine learning classification models.

Task 1: Exploratory Data Analysis(Iris Dataset)

Objective:

To understand the structure of the Iris dataset and explore relationships between features using visualizations.

Approach

Loaded dataset using pandas Checked shape, columns and summary statistics Performed data visualization: Scatter plots Histograms Pairplot for feature relationshis and Boxplots for data distribution.

Results

Clear seperation observed between species based on petal features Setosa species was easily distinguisable from other

Insights

Petal length and petal width are strong indicators for classifation some features are highly correlated.

Task 2: Loan Default Prediction(loan_default_prediction dataset)

Objective:

To predict whether a loan applicant will default based on financial and personal data.

Approach:

Data cleaning and handling missing values. Encoding categorical variables. Visualization feature scaling model training using classification algorithm(Logistic Regression)

Results:

The datasets was preprocessed by encoding categorical variables and applying feature scaling using StandardScaler. A Logistic Regression model was trained to predict loan default risk. Stratified sampling was used during the train-test split to maintain class distribution, which improves model performance. The final model acheive an accuracy of 69%, indicating that the model correctly predicts the loan default status for the majority of the cases.
Evaluation using confusion matrix and classification report showed that the model performs reasonably well identifying the defaulters and non-defaulters.

Insights:
Income, loan amount and employment_status are strong predictors of loan default.

Task 3: Churn Prediction(bank_churn dataset)

Objective:

To identify customer churn and identify key factors influencing customer retention.

Approach:

Data preprocessing and encoding Train-test split Model training(Random Forest) Pipeline and hyperparameter tuning were performed to get the better results. Evaluating using accuracy, confusion matrix, ROC-AUC, classification report.

Results

The Random Forest model acheived an accuracy of 67% and a ROC-AUC score of 0.58, showing good overall performance in predicting customer exit behaviour. The confusion matrix indicates that the most customers were classified correctly, including 1186 non-exited and 170 exited customers. The classification report shows strong performance for non-exited customers and moderate performance for exited customers, with the correctly identifying about 40% of customers who exited the bank.

Insights

The key factors affecting customer exit behaviour, such as age, balance, or amount activity. Class imbalance affected model performance using SMOTE.










