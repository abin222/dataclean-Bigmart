# Big Mart Data Cleaning and Feature Engineering Project

## Project Overview

This project involves cleaning, preprocessing, and feature engineering for the Big Mart dataset to prepare it for further analysis and predictive modeling. The project handles common issues in raw data, such as missing values, inconsistencies, and outliers, while creating new features to enhance the dataset's analytical power.

---

## Files in the Repository

- **`bigmart.csv`**:  
  The raw dataset containing sales data for various products across multiple outlets.

- **`Big Mart Feature Engineering.ipynb`**:  
  A Jupyter Notebook that details the cleaning, preprocessing, and feature engineering steps applied to the dataset.

---

## Data Cleaning Steps

The following tasks were performed on the dataset:

1. **Loading the Data**:  
   - Imported the CSV file using `pandas` into a DataFrame for processing.

2. **Handling Missing Values**:  
   - Identified columns with missing data.
   - Applied appropriate imputation strategies:
     - Mean/Median for numerical data.
     - Mode for categorical data.

3. **Standardizing Categorical Data**:  
   - Unified inconsistent labels in categorical columns.
   - Encoded categorical variables for analysis and modeling.

4. **Outlier Detection and Treatment**:  
   - Used visualizations (e.g., box plots, histograms) to detect outliers.
   - Treated outliers through capping or log transformations.

5. **Feature Engineering**:  
   - Added new features to enrich the dataset, such as:
     - Age of the store based on the establishment year.
     - Binned item prices into ranges for better segmentation.

6. **Scaling and Normalization**:  
   - Applied scaling methods (e.g., Min-Max, Standard Scaler) to numerical features.

7. **Exporting Cleaned Data**:  
   - Saved the cleaned and processed dataset to a new CSV file for further use.

---

## Feature Engineering Highlights

- Created new variables to capture underlying patterns.
- Enhanced categorical features through one-hot encoding.
- Reduced dimensionality by grouping similar categories.

---

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `jupyter`

---

## How to Use

1. Place the `bigmart.csv` file in the project directory.

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Big Mart Feature Engineering.ipynb"
