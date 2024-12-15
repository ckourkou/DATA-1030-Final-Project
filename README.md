# Predicting Draft Round for College Football Players
This project uses data from Stathead to predict which round in the NFL draft college football players were selected in, or if they went undrafted. 
The data contains key metrics for passing, rushing, and receiving, as well as games played, years played, and team.
Four ML classification models (XGBoost, Random Forest, Support Vector Classifier, KNN Classifier) are fit and evaluated by accuracy.

# Repo Structure
- **data/**: contains original datasets as well as raw/preprocessed training/testing data for three random states
- **figures/**: contains charts/graphs of EDA, results, interpretability
- **results/**: contains saved models and predictions for each model in each random state
- **report/**: contains PDF report write-up of project
- **src/**: contains source code of python file


# Packages
The following packages and versions are used for this project
- python=3.12.5
- matplotlib=3.9.2
- plotly=5.23.0
- pandas=2.2.2
- scikit-learn=1.5.1
- numpy=1.26.4
- py-xgboost=2.1.1
- shap=0.45.1
