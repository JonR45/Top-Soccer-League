# Does a soccer player play in one of Europe's top 5 leagues?
The aim of this mini-project was to create a model that could predict if an outfield soccer played in one of the top 5 European leagues based on physical and technical data from the FIFA 23 daataset.

# Overview
* The FIFA dataset contains details of soccer players' physical characteristics and technical capabilities.

![dataset](https://github.com/JonR45/Top-Soccer-League/blob/main/Images/Dataset.png)

* There are 5 leagues in Europe generally regarded as the highest level of competition; these leagues are: the English Premier League (EPL), the Italian Serie A, the Spanish La Liga, the German Bundesliga, and the French Ligue 1.
* The project used XGBoost to create a model that predicted, based on physical and technical ratings, whether a soccer player plays for a team in one of the top 5 European leagues.

# Langauges and Packages
**Language:** Python (version 3.10)


**Packages:** pandas, numpy, matplotlib, sklearn, XGBoost, shap, imblearn, Optuna

# Visuals
### Balancing the dataset with SMOTE

![balance_pre_smote](https://github.com/JonR45/Top-Soccer-League/blob/main/Images/training_data_pre-balance.jpg)

![balance_post_smote](https://github.com/JonR45/Top-Soccer-League/blob/main/Images/training_data_post-balance.jpg)


### Shapley values for feature importance

![shap_values](https://github.com/JonR45/Top-Soccer-League/blob/main/Images/shap_summary_plot.jpg)

### Optuna and RandomizedSearchCV for hyperparameter tuning

![hyperparameter_importance](https://github.com/JonR45/Top-Soccer-League/blob/main/Images/Hyperparameter_importance.png)

# Results
![results](https://github.com/JonR45/Top-Soccer-League/blob/main/Images/model_evaluation.png)

# Next steps
- This project could be developed further by trying other classifiers and comparing their performance.

# Data
- The data used for this project was the <a href="https://www.kaggle.com/datasets/stefanoleone992/fifa-23-complete-player-dataset" target="_blank">FIFA 23 dataset</a> available on Kaggle.

# License
This project is licensed under the terms of the MIT License. See the LICENSE.txt file for details.
