# Credit-Card-Fraud-Detection
Analysed and visualised credit card transactions, then build a machine learning model to detect fraudulent transactions
The data set can be found at: https://www.kaggle.com/datasets/kartik2112/fraud-detection

In the main notebook, I pre-process the raw data from kaggle and perform feature engineering, before performing some exploratory data analysis.
After this, in the ml notebook I start to experiment with different machine learning models to optimise precision and recall due to the imbalanced nature of the data.

I experimented with:
- Logistic Regression
- Random Forest
- CatBoost

My final model managed to achieve an average accuracy of 0.9994, average precision of 0.978, average recall of 0.926 and average f1 score of 0.95 across 5 cross validation folds.

Written reflection of the steps, approaches and decisions I made during this analysis can be found documented throughout the notebooks linked.
    

