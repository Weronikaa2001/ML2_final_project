FINAL PROJECT – MACHINE LEARNING 2
Predictive Models, Deep Learning, Neural Networks
Course instructor: Ewa Weychert
============================================================

FOLDER STRUCTURE

.
├── ML2_regression_part1.ipynb
├── ML2_regression_part1.html            
├── ML2_regression-part2.ipynb
├── ML2_regression-part2.html           
├── OnlineNewsPopularity.csv
├── title_class-n.png
└── README_regression.txt           

============================================================

REGRESSION PROJECT
"Online News Popularity"

============================================================

Goal:
Predict continuous labels using ML regression models.

Dataset:
Mashable news dataset (39,644 articles, 61 variables).

Targets:
1. shares - initially
2. global_subjectivity - in the second take

Models:
- Random Forest
- Gradient Boosting
- XGBoost
- SVR
- Elastic Net

Evaluation:
- RMSE (lower = better)
- R² (higher = better)
- 80/20 train-test split + cross-validation + hyperparameter tuning

PART 1 Results:
- Very weak correlations of target with features
- Models achieved poor performance 
- Many attempts (encoding, feature selection, outliers, tuning) had little impact
- Conclusion: the target variable was correlated to weakly to have meaningful results, also it was highly-skewed

PART 2 Results:
- Much stronger correlations with features
- Models achieved relatively high performance 
- XGBoost and Gradient Boosting performed best
- Predictions aligned well with actual values
- Conclusion: subjectivity is learnable because related features are present

Key Takeaways:
- Target choice matters
- Data must contain information relevant to the target
- Poor results are informative (problem formulation issue, not modeling issue)

Best Model:
XGBoost (highest R² and lowest RMSE)

============================================================

AUTHORS

Project developed by Weronika Mądro and Yuliya Martyniuk as part of the
Machine Learning 2 course (Predictive Models, Deep Learning, Neural Networks)
at the University of Warsaw, Faculty of Economic Sciences.

============================================================