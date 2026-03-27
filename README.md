# Bangladesh Child Mortality Prediction

Predicts the child mortality rate in Bangladesh using socioeconomic 
indicator data from the World Bank, comparing a classical 
regression baseline with a machine learning approach.

## Data
World Bank Open Data - Bangladesh country indicators  
Source: https://data.worldbank.org/country/BD

## Tools
Python · pandas · scikit-learn · matplotlib · seaborn

## Models
- Linear Regression (R²=0.976, RMSE=13.598)
- Random Forest Regressor (R²=0.907, RMSE=26.539)

## Key findings
Linear Regression outperformed Random Forest, reflecting the 
consistent downward trend in child mortality in Bangladesh 
across decades. Urban population percentage and GDP per capita 
were the strongest predictors of child mortality outcomes.

## How to run
1. Clone this repository
2. Place `bangladesh_indicators.csv` in the root folder
3. Open `bangladesh_poverty_prediction.ipynb` in Jupyter
4. Run all cells in order
