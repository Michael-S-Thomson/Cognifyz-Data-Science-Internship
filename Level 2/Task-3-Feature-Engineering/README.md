# Level 2 - Task 3: Feature Engineering

## Objective

Create additional features from the restaurant dataset to make the data more useful for analysis and machine learning.

## Features Created

### 1. Restaurant Name Length

Calculated the number of characters in each restaurant name.

### 2. Address Length

Calculated the number of characters in each restaurant address.

### 3. Table Booking Encoding

Converted the `Has Table booking` categorical feature into a numerical feature:

* `Yes` → `1`
* `No` → `0`

### 4. Online Delivery Encoding

Converted the `Has Online delivery` categorical feature into a numerical feature:

* `Yes` → `1`
* `No` → `0`

## Final Dataset

The original dataset contained:

* 9,551 rows
* 21 columns

Four additional features were created, resulting in:

* 9,551 rows
* 25 columns

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Files

* `Task3.ipynb` - Complete feature engineering analysis
* `README.md` - Task description and results

## Dataset

The dataset was used locally during the analysis.

The CSV dataset is not included in the GitHub repository because CSV files are excluded through `.gitignore`.

## Conclusion

Feature engineering successfully converted existing textual and categorical information into useful numerical features.

The new features can be used in subsequent exploratory analysis and machine learning models.
