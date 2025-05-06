# Titanic Disaster Survival Prediction

This project is part of the Titanic Kaggle competition. The goal is to predict survival outcomes based on passenger information using machine learning models.

##  Objective

- Predict whether a passenger survived the Titanic disaster using demographic and passenger data.
- link Kaggle `https://www.kaggle.com/code/tinguyntrng/titanic`
## Tools & Technologies

- Python
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `sklearn` for modeling
  - `xgboost` or other models (depending on notebook)

##  How to Run

1. Clone the repository.
2. Ensure required packages are installed (listed in `requirements.txt` - `pip install -r requirements.txt` or install manually).
3. Open the Jupyter notebook `titanic.ipynb`.
4. Active cuda and Run all cells to:
   - Load and preprocess data
   - Train and validate the model
   - Generate predictions for submission

##  Model Performance

- **Validation Accuracy**: ~85%
- **Kaggle Submission Score**: ~76%

> Note: The drop in performance from validation to Kaggle score may indicate overfitting or differences in test data distribution.

##  Project Structure
-  ├── data/
-  │   ├── train.csv
-  │   ├── test.csv
-  │   └── README.md      
-  ├── notebooks/
-  │   └── titanic_analysis.ipynb
-  ├── src/
-  ├── outputs/
-  │   ├── model.pkl
-  │   └── submission.csv
-  ├── requirements.txt
-  ├── README.md
-  └── .gitignore

