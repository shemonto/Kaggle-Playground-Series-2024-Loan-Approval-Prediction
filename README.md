# Kaggle-Playground-Series-2024-Loan-Approval-Prediction

## Objective
- Developed a predictive model to determine the likelihood of an applicant’s loan approval, honing skills in classification modeling.

## Dataset
- Engaged with a synthetic, tabular dataset modeled on real-world data to simulate a loan approval scenario.

## Techniques

### Step1: Data Preprocessing
- Conducted data loading, merging, checking for duplicates and handling NaNs. 

### Step2: Exploratory Data Analysis (EDA)
- Conducted visualizations and statistical analysis to understand feature distributions and relationships.

### Step3: Feature Engineering
- Created new variables, transformed features, and optimized data representation for improved model performance.

### Step4: Model Selection and Training 
- Experimented with classification algorithms, including:
  - ExtraTrees
  - XGBoost
  - Random Forest
  - Gradient Boosting
  - CatBoost
  - LightGBM
- Identified the best-performing model based on stratified cross validation score.
- Hyperparameter Tunning

### Step5: Model Evaluation 
- Optimized for the following metrics:
  - F1-score
  - Precision
  - Recall
- Confusion matrix for the best performing model  
- ROC curve to see how well the classifier seperates the classes.  
- Assessed the model's predictive capabilities accross different probability thresholds.
- Learning Curves to check overfitting

### Step6: Blending and Stacking models
- Blended the best performing classifiers using weighted voting classifiers
-  stacked best performing classifiers with LogisticRegression as final estimator 

### Step7: # Prediction on Kaggle Test Data
- Performed the preprocessing and feature engineering steps on test data
- Generated predicted probalities on test set using catboost classifier 

## Achievements
- Achieved a final AUC score of 0.96 on kaggle's test set, demonstrating a deep understanding of the machine learning workflow, from data preprocessing to model deployment.

## Outcome
- Enhanced skills in data handling, model tuning, and iterative improvement of classification models, further solidifying expertise in applied machine learning.
