# Titanic - Dataset Overview

This dataset is part of the famous Titanic - Machine Learning from Disaster competition on Kaggle. It provides passenger data used to predict who survived the tragedy.

##  Dataset Files

- `train.csv`: Contains the labeled training data (including survival labels).
- `test.csv`: Contains the unlabeled test data used for submission.
- `gender_submission.csv`: An example submission file.
- `submission.csv`: The final model prediction result (based on the test set).

##  Features Description

- `PassengerId`: Unique ID for each passenger.
- `Survived`: Target variable (0 = No, 1 = Yes).
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- `Name`: Full name of the passenger.
- `Sex`: Gender.
- `Age`: Age in years.
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Ticket`: Ticket number.
- `Fare`: Passenger fare.
- `Cabin`: Cabin number.
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

##  Create new feature
- create new feature `Family_size` from Sibsp and Parch
##  Data Cleaning Performed

- Missing values in `Age`, `Cabin`, and `Embarked` were handled via:
  - Filling `Age` with median/mean.
  - Dropping or imputing `Cabin` 
  - Imputing `Embarked` with the mode.

## 📊 Data Split

- `train.csv` was split into training and validation sets.
- Accuracy on validation set: **85%**
- Accuracy on Submission: **76%**

