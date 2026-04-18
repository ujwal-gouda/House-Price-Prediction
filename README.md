# House Price Prediction using Machine Learning

## Overview
This project aims to predict house prices using multiple machine learning regression models. The dataset contains various features such as area, number of bedrooms, bathrooms, and other property-related attributes. The objective is to build models that can accurately estimate house prices and compare their performance.

## Dataset
The dataset used in this project is sourced from Kaggle:

Housing Prices Dataset  
https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

It includes features such as:
- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Furnishing status
- Additional categorical features


## Features
- Data preprocessing using one-hot encoding for categorical variables  
- Implementation of multiple regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Model evaluation using K-Fold Cross Validation  
- Performance metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
- Visualization of results using bar graphs  


## Dataset
The dataset contains housing-related attributes such as:
- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Furnishing status
- Other categorical features


## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  


## Methodology
1. Data preprocessing using pandas and one-hot encoding  
2. Splitting data using K-Fold Cross Validation  
3. Training multiple regression models  
4. Evaluating model performance using MSE and RMSE  
5. Comparing results across models  
6. Visualizing performance using bar charts  


## Results
The models were evaluated using cross-validation, and performance was compared using RMSE and MSE values. The model with the lowest RMSE was selected as the best-performing model.


## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ujwal-gouda/House-Price-Prediction.git
   ```
2. Install Required Libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```
3. Run the notebook or script:
   ```bash
   python your_script.py
   ```


## Future Improvements
- Include more features such as location-based data
- Improve model performance using advanced algorithms
- Build a web application using Flask or React
- Deploy the model for real-time predictions


## Conclusion
This project demonstrates the use of multiple machine learning models for regression tasks and highlights the importance of proper model evaluation using cross-validation techniques.
