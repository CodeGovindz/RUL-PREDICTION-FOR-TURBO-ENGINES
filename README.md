# RUL PREDICTION FOR TURBO ENGINES
The "RUL Prediction for Turbo Engines" repository contains code and resources for a predictive maintenance project focused on forecasting the Remaining Useful Life (RUL) of turbofan engines using machine learning techniques.
It is designed to work seamlessly with CMAPSS (Commercial Modular Aero-Propulsion System Simulation) datasets, which are widely used in the aerospace industry for RUL prediction tasks. 
# Features
  ## Data Preprocessing: 
    Cleaning and preparing the raw dataset for analysis.
  ## Feature Selection:
    Removal of low correlated features (correlation in the range - [-0.001,0.001])
    Removal of highly correlated features (correlation greater than 0.9)
    Removal of low variance features (features with 2 unique values and a ratio greater or equal to 0.95)
  ## Model Training and Evaluation:
    Traineing machine learning models and evaluating their performance.
  ## Visualization: 
    Generating plots to visualize the results and insights.
