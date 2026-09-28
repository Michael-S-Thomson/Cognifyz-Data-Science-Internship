# Level 1 - Task 3: Geospatial Analysis

## Objective

Perform geospatial analysis on the restaurant dataset by:

- Visualizing restaurant locations using latitude and longitude.
- Analyzing the distribution of restaurants across cities and countries.
- Examining the relationship between restaurant location and aggregate rating.

## Dataset

The analysis was performed using the cleaned restaurant dataset provided for the internship.

The dataset is not included in this repository because the dataset file is excluded through `.gitignore`.

## Analysis Performed

### 1. Geographical Distribution

Restaurant locations were visualized using Latitude and Longitude coordinates.

The scatter plot shows that restaurants are concentrated in specific geographical regions rather than being evenly distributed.

### 2. City Distribution

The number of restaurants was analyzed across different cities.

**Most represented city:** New Delhi

**Number of restaurants:** 5,473

### 3. Country Distribution

Restaurant counts were analyzed using Country Code.

**Most represented Country Code:** 1

**Number of restaurants:** 8,652

### 4. Location and Rating Analysis

The relationship between geographical coordinates and Aggregate Rating was examined using correlation analysis.

- Latitude vs Aggregate Rating: approximately **0.001**
- Longitude vs Aggregate Rating: approximately **-0.117**

These values indicate a very weak linear relationship between geographical coordinates and restaurant ratings.

## Key Findings

- Restaurant locations are geographically concentrated in specific regions.
- New Delhi is the most represented city in the dataset.
- Country Code 1 contains the majority of restaurants.
- Latitude has an almost negligible linear relationship with Aggregate Rating.
- Longitude has a weak negative linear relationship with Aggregate Rating.
- Location alone does not strongly explain differences in restaurant ratings.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Files

- `Task3.ipynb` - Complete geospatial analysis notebook.
- `README.md` - Task description, methodology, and findings.

