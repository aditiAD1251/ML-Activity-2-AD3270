# Activity 2 – Simple House Price Prediction
## Activity details
Course Name - Machine Learning
Activity - CIE 2 – Activity 2
Activity Title - Simple House Price Prediction

## Project Description
This project uses Simple Linear Regression to predict house sale prices using the Ames Housing Dataset.

## Dataset Information
- **Dataset Name:** Ames Housing Dataset
- **File Type:** CSV
- **Original Dataset Shape:** 2930 rows × 82 columns
- **Input Feature (X):** Gr Liv Area (Above Ground Living Area)
- **Target Variable (y):** SalePrice

## Dataset Source
[Kaggle – Ames Housing Dataset]( https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset)

## Files Included
1. `AmesHousing.csv` – Original dataset.
2. `AmesHousing_Cleaned.csv` – Cleaned and prepared dataset.
3. `Activity_2_Ames_House_Price_Prediction_Aditi.ipynb` – Complete Google Colab notebook.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Steps Performed
1. Importing libraries and loading the dataset.
2. Inspecting the dataset.
3. Checking missing values and duplicate records.
4. Handling missing values.
5. Selecting input feature and target variable.
6. Visualising the relationship between living area and sale price.
7. Splitting data into training and testing sets (80:20).
8. Training the Linear Regression model.
9. Generating predictions.
10. Evaluating the model using MAE, MSE, RMSE and R².
11. Visualising actual vs predicted prices.
12. Predicting the price of a new house.

## Model Evaluation Results

The Linear Regression model was evaluated using the following metrics:

| Evaluation Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 41,365.51 |
| Mean Squared Error (MSE) | 3,821,184,066.27 |
| Root Mean Squared Error (RMSE) | 61,815.73 |
| R-squared (R²) | 0.5234 |

### Interpretation of Results

1. **MAE:** The model's predictions differ from actual house prices by an average of approximately 41,365.51 price units.
2. **MSE:** It measures the average squared difference between actual and predicted house prices. Larger errors receive more weight.
3. **RMSE:** The typical prediction error is approximately 61,815.73 price units, expressed in the same unit as house prices.
4. **R² Score:** The model explains approximately 52.34% of the variation in house prices using the selected input feature, Gr Liv Area.

### Result Summary

The Linear Regression model shows a moderate ability to predict house prices using above-ground living area. However, other factors such as location, number of rooms and overall house quality may also influence house prices and are not included in this single-feature model.

## Conclusion
A Simple Linear Regression model was developed using Gr Liv Area to predict SalePrice. The model was evaluated using regression metrics and actual-versus-predicted visualisation.

## Faculty Profile and Acknowledgement

Faculty Profile: [Princy2129](https://github.com/Princy2129)

This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources:
https://github.com/Princy2129
