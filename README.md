# INM701: Introduction to Artificial Intelligence

### Team Members: 

- Cam Nguyen

- Marium Waseem 

Kickstarter Success Predictor – INM701
Kickstarter Success Predictor is a machine learning project developed for INM701 coursework by Marium Waseem and Cam Nguyen. It aims to predict the success of crowdfunding campaigns using historical Kickstarter data and classification models.

 Project Overview
- Analyzed 300,000+ Kickstarter projects from Kaggle
- Implemented and evaluated 5 machine learning models
- Used Scikit-learn, PCA, SMOTE, and GridSearchCV
- Identified key predictors of project success such as goal size, campaign length, and category

 ML Models Used
- Dummy Classifier (baseline)
- Gaussian Naive Bayes
- Bernoulli Naive Bayes
- Logistic Regression
- K-Nearest Neighbors
- Random Forest

Key Findings
- Best performance achieved by Random Forest with:
- Accuracy: 64.32%
- Precision: 65.84%
- Recall: 64.32%
- F1 Score: 64.65%
- ROC AUC: 70.47%

- All models were better at predicting failed campaigns than successful ones
- Features like goal size, category, and campaign length were the strongest predictors

Techniques Used
- Feature engineering (campaign length, goal log, name metrics)
- Dimensionality reduction using PCA
- Class imbalance handled using SMOTE
- Model tuning via GridSearchCV
- Evaluation metrics: Accuracy, Precision, Recall, F1 Score, ROC AUC
