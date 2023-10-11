# Heart_Disease_Prediction
Exploratory Data Analysis (EDA):

Categorized data into categorical and continuous values.
Conducted univariate analysis using bar plots for categorical features and probability density plots for numerical features to understand variable distribution.
Performed bivariate analysis to explore relationships between features and the target variable.
Utilized multivariate analysis, including correlation matrix, to identify significant features.
Conducted outlier analysis to identify and handle outliers.
Standardized data through resampling for handling unbalanced datasets and feature scaling to standardize continuous features.

ALGORITHM:

Stacking is one of the popular ensemble modeling techniques in machine learning. Various weak learners are ensembled in a parallel manner in such a way that by combining them with Meta learners, we can predict better predictions for the future.

Base Learner 1: XGBoost 

Base Learner 2: Decision Tree Classifier

Base Learner 3: Random Forest

Meta Learner: Logistic Regression

Level-0 Models (Base-Models): Models fit on the training data and whose predictions are compiled.

Level-1 Model (Meta-Model): Model that learns how to best combine the predictions of the base models.
![image](https://github.com/Kruthi16/Heart_Disease_Prediction/assets/108337356/44ee658b-9e70-40a4-ab4a-15a4b8e5e017)
