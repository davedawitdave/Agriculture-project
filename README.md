
# Agricultural Dataset Analysis

## Overview
This repository contains code and analysis for exploring and analyzing a comprehensive agricultural dataset. The dataset comprises various geographic, weather, soil, and farm management features, aiming to uncover relationships between these factors and agricultural yield.

## Objective
The primary objective of this project is to develop predictive models that can provide actionable insights for farmers to improve productivity and make informed decisions. By analyzing the dataset, we aim to achieve the following objectives:

- Analyze predictor variables and their relationship with the target variable.
- Perform feature engineering tasks, including encoding categorical variables and scaling features.
- Construct and evaluate multiple linear regression models using appropriate libraries.
- Identify and address multicollinearity issues using regularization techniques such as LASSO and Ridge regression.
- Interpret regression coefficients and understand their impact on the target variable.
- Implement decision tree models for prediction tasks, exploring both categorical and numerical data.
- Calculate and interpret Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) for model evaluation.
- Implement different machine learning models including Decision tree, support vector machine regression, random forest
- Perform Hyperparameter tuning for each of the above machine-learning models and implement heterogeneous stacking ensembling.

## Dataset Description
The dataset includes the following features:

### Geographic Features
- **Field_ID**: Unique identifier for each field.
- **Elevation**: Elevation of the field above sea level.
- **Latitude**: Geographical latitude of the field.
- **Longitude**: Geographical longitude of the field.
- **Location**: Province the field is in.
- **Slope**: The slope of the land in the field.

### Weather Features
- **Rainfall**: Amount of rainfall in the area.
- **Min_temperature_C**: Average minimum temperature recorded.
- **Max_temperature_C**: Average maximum temperature recorded.
- **Ave_temps**: Average temperature.

### Soil and Crop Features
- **Soil_fertility**: Measure of soil fertility.
- **Soil_type**: Type of soil present in the field.
- **pH**: pH level of the soil.

### Farm Management Features
- **Pollution_level**: Level of pollution in the area.
- **Plot_size**: Size of the plot in the field.
- **Chosen_crop**: Type of crop chosen for cultivation.

### Target Variable
- **Standard_yield**: Standardized yield expected from the field.

## Usage
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd agricultural-dataset-analysis`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the analysis notebook: `jupyter notebook agricultural_analysis.ipynb`

## Conclusion
This project aims to provide valuable insights into agricultural yield prediction using various machine-learning techniques. Through analysis and modeling, we can develop predictive models that help optimize farming practices and increase productivity.
## Future work 
We aim to add crop recommendations for the particular terrain.
## Contributors
- [Dawit Asmero](https://github.com/davedawitdave)
- Data from the ExploreAI open dataset

## License
This project is licensed under the [Apache License 2.0](LICENSE).








