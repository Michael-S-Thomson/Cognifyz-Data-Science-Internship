# Level 1 - Task 1: Data Exploration and Preprocessing

## Cognifyz Data Science Internship

### Objective

The objective of this task is to explore and preprocess the restaurant dataset by understanding its structure, handling missing values, checking duplicate records, converting data types, and analyzing the distribution of aggregate ratings.

## Dataset Overview

- **Number of Rows:** 9,551
- **Number of Columns:** 21
- **Dataset Type:** Restaurant information and ratings

## Tasks Performed

### 1. Dataset Exploration

The dataset was loaded using Pandas and its structure, columns, data types, and statistical information were examined.

### 2. Missing Value Analysis

Missing values were identified using Pandas.

The `Cuisines` column contained **9 missing values**.

These missing values were handled using the most frequent value (mode) of the `Cuisines` column.

After preprocessing:

- **Missing values:** 0

### 3. Duplicate Check

The dataset was checked for duplicate records.

- **Duplicate rows:** 0

### 4. Data Type Conversion

The following columns were converted to appropriate numeric data types:

- `Aggregate rating`
- `Votes`
- `Price range`

### 5. Aggregate Rating Analysis

The distribution of the `Aggregate rating` column was analyzed using statistical summaries and visualizations.

The aggregate rating ranges from **0.0 to 4.9**.

The dataset contains **2,148 restaurants with an aggregate rating of 0.0**, representing approximately **22.49%** of the dataset.

The rating distribution is therefore imbalanced, with a significant concentration in the 0.0 rating category.

## Visualizations

The notebook contains visualizations for:

- Aggregate Rating Distribution
- Aggregate Rating Frequency

## Final Preprocessing Results

| Metric | Result |
|---|---:|
| Rows | 9,551 |
| Columns | 21 |
| Missing Values | 0 |
| Duplicate Rows | 0 |
| Restaurants with Rating 0 | 2,148 |
| Rating 0 Percentage | 22.49% |

## Conclusion

The restaurant dataset was successfully explored and preprocessed. Missing values in the `Cuisines` column were handled, duplicate records were checked, and relevant numerical columns were converted to appropriate data types.

The aggregate rating distribution was also analyzed and found to be imbalanced, with a substantial number of restaurants belonging to the 0.0 rating category.

The cleaned dataset is now prepared for further analysis.

## Files

- `Task1.ipynb` - Jupyter Notebook containing the complete analysis and code.
- `Cognifyz_Cleaned_Dataset.csv` - Cleaned dataset generated during preprocessing.
- `Task-1-Data-Exploration.pdf` - Report containing the analysis, visualizations, and conclusions.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook