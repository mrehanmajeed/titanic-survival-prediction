## Titanic-Survival-Prediction
This project uses the famous Titanic dataset to predict whether a passenger survived or not, based on features such as age, gender, passenger class, and more.
It’s a beginner-friendly machine learning project that covers data cleaning, feature engineering, model training, and evaluation.

## Dataset
train.csv → Training dataset with labels (Survived/Not Survived)
test.csv → Test dataset without labels (for predictions)
gender_submission.csv → Example submission file

## Project Workflow
# Data Loading & Exploration
Load train/test datasets
Explore features, missing values, and distributions
# Data Preprocessing
Handle missing values (Age, Fare, Embarked)
Encode categorical variables (Sex, Embarked)
Select useful features (Pclass, Sex, Age, SibSp, Parch, Fare, Embarked)
# Model Training
Logistic Regression
Decision Tree Classifier
# Model Evaluation
Accuracy Score
Confusion Matrix
# Classification Report
Final Submission
Generate predictions on the test set
Save results in submission.csv
## Results
Logistic Regression Accuracy: ~78–82% (depending on split & preprocessing)
Decision Tree Accuracy: ~75–80%
(Accuracy may vary slightly due to randomness in train-test splits.)
## Tech Stack
Python
Jupyter Notebook
pandas, numpy, matplotlib, seaborn (data analysis & visualization)
scikit-learn (machine learning models & evaluation)
## Files in Repo
Titanic_Survival_Prediction.ipynb → Main Jupyter Notebook with full workflow
train.csv → Training dataset
test.csv → Test dataset
gender_submission.csv → Sample submission file
submission.csv → Final model predictions
## How to Run
Open Titanic_Survival_Prediction.ipynb in Jupyter Notebook / Jupyter Lab
Run all cells step by step
The final predictions will be saved as submission.csv
