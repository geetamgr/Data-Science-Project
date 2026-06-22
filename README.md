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














