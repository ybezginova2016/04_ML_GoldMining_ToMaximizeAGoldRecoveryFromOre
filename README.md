# 04_ML_GoldMining_ToMaximizeAGoldRecoveryFromOre
To prepare a machine learning prototype model for predicting a coefficient of recovery of gold from the ore in order to find a solution to overcome the challenges of declining ore grades, remove parameters, which do not help increase the gold recovery, and to keep gold mining economically viable.

## Research Question
How to maximize output from a gold reserve?

## Project objective
To prepare a machine learning prototype model for predicting a coefficient of recovery of gold from the ore in order to find a solution to overcome the challenges of declining ore grades, remove parameters, which do not help increase the gold recovery, and to keep gold mining economically viable.

## Data provided:
- Gold mining and ore cleaning parameters.
- 3 separate datasets given - all, rougher, final;

## Project Methodology
1. Data loading, pre-processing
2. Exploratory data analysis.
3. sMAPE is used as a quality metrics.
4. Cross validation is used for choosing the best model.
5. Features scaling.
6. Machine learning modelling, choosing the best model with most suitable hyperparameters, which is able to predict a continuous variable of a coefficient of gold recovery from the ore.
7. Make conclusions and recommendations for business, which parameters influence the gold recovery most and should be considered more carefully in the technological process.

### Key Python Libraries: 
- plotly, seaborn, scipy
- sklearn.linear_model
- sklearn.metrics
- sklearn.ensemble
- sklearn.tree


### Project Code: https://github.com/ybezginova2016/04_ML_GoldMining_ToMaximizeAGoldRecoveryFromOre/blob/main/04_ML_GoldMining_main.ipynb
