# Solar-Radiation-Linear-Regression

## Backgroud and Goal
Solar radiation measurement is hard and costs much. The goal of this project is to build a regression model to predict the solar radiation as accurate as possible.

## File Descriptions
### SolarPrediction.csv
- The original dataset
- Kaggle was the last destination in the provenance of the data
- Original source: NASA
- Variables captured within the dataset are solar radiation, temperature, humidity, barometric pressure, wind direction, wind speed, and sunrise/sunset based on Hawaii time.

### DataWrangling.ipynb
- A Jupyter Notebook to clean and wrangle the data
- A look at the data: data types, distributions of numerical fields
- Data cleaning
- Feature engineering: add dummy variables and higher-order terms
- Correlation matrix 

### Solar_Features.csv
- The output file from DataWrangling.ipynb

### LinearRegression.ipynb
- A Jupyter Notebook to build linear regression models
- Model 1: Linear Regression (No Higher-Order Terms)
- Model 2: Linear Regression (With Higher-Order Terms)
- Model 3: Ridge Regression
- Model 4: Lasso Regression

## Best Result
### R squared = 0.7248
