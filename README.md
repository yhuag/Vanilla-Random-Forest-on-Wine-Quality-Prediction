# Vanilla Random Forest on Wine Quality Prediction

## Project Intro
The project trained a vanilla random forest model on 1.6K data of red wine to predict its quality. 

## Steps
- Import Libraries
- Data Loading
- Data Spliting (training set and testing set)
- Data Preprocessing (`StandardScaler` to collect the mean and sd from training dataset and applying on the testing dataset later on via pipelining). Embed `RandomForestRegressor` as trainer.
- Hyperparameter Setup
- Cross-validation (`GridSearchCV`)
- Evaluation

## Reference
The code is based on a comprehensive tutorial from Elite Data Science [here](https://elitedatascience.com/python-machine-learning-tutorial-scikit-learn)

