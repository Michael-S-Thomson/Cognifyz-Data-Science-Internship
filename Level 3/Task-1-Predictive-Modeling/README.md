# Level 3 - Task 1: Predictive Modeling

## Objective

Build regression models to predict the Aggregate Rating of restaurants using relevant features from the restaurant dataset.

## Features Used

The following features were used for prediction:

- Price range
- Votes
- Has Table Booking Encoded
- Has Online Delivery Encoded
- Restaurant Name Length
- Address Length

### Target Variable

- Aggregate rating

## Methodology

The following steps were performed:

1. Loaded the restaurant dataset.
2. Created required numerical features.
3. Selected relevant features for prediction.
4. Split the dataset into training and testing sets.
5. Trained three regression models:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
6. Evaluated the models using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score
7. Compared the model performance.
8. Analyzed Random Forest feature importance.

## Model Performance

| Model | MAE | MSE | RMSE | R² |
|---|---:|---:|---:|---:|
| Linear Regression | 1.0757 | 1.6779 | 1.2953 | 0.2628 |
| Decision Tree | 0.2366 | 0.1320 | 0.3633 | 0.9420 |
| Random Forest | 0.2226 | 0.1155 | 0.3399 | 0.9492 |

## Dataset Split

The dataset was divided into:

- 80% training data
- 20% testing data
- Random state: 42

## Evaluation

MAE, MSE, RMSE, and R² were used to evaluate the regression models.

Lower MAE, MSE, and RMSE indicate smaller prediction errors, while a higher R² indicates that the model explains more variation in the target variable.

## Conclusion

Three regression models were developed and evaluated for predicting restaurant Aggregate Rating.

The model performance differed substantially across the tested algorithms. The results provide a comparison of linear and tree-based regression approaches for this dataset.

The Random Forest model achieved an R² score of approximately 0.949 on the test set, with an RMSE of approximately 0.340.

These results describe performance on the available test split and should not be interpreted as proof that the model will perform identically on unseen datasets.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Files

- `Task1.ipynb` - Complete predictive modeling analysis
- `README.md` - Task description, methodology, results, and conclusion



