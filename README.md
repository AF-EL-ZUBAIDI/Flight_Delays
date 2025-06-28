# Flight Delays Prediction

The goal of this project was to build a machine learning model that predicts whether a flight will be delayed by more than 15 minutes. This data concerns the departure flights from JFK Airport in 2024.


## About this project
- Merges 2024 JFK flight data with hourly weather data
- Cleans the dataset and creates new features based on real-world weather conditions
- Trains classification models: Logistic Regression, Random Forest, and XGBoost
- Tunes model hyperparameters for better performance

## Best model result
XGBoost gave the best performance with:
- **Accuracy:** 93.6%
- **F1 Score:** 83.8%
- **Train/Test split:** 90/10

### Note
The notebook is not directly executable without the datasets (files are too large for GitHub). 
However, the full logic and steps are available and explained.
