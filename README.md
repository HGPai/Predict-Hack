# Predict-Hack
The dataset consists of financial transaction data. It contains an 'Incident_ID' column, a 'Date' column and
15 anonymous feature columns. The Target labels mentioned in the column 'MULTIPLE_OFFENSE' are 0 and 1.
The goal of this Machine Learning project is to predict if an instance was a hack or not with a hack being 1
and not a hack being 0.

The project was executed in the following manner:
1. Read the data
2. Basic Exploratory Data Analysis
3. Preprocessing
4. Model Building
5. Evaluation
6. Generalizing the model and building a function to test new data.

The algorithms used for model building were : Support Vector Machine, Random Forest, Gradient Boosting Trees and 
XGBoost. XGBoost was chosen as the final model.

The evaluation metric chosen was recall score. The recall score obtained for this exercise was 0.983
