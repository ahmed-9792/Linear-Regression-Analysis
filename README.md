Linear Regression Analysis

Objective:
To implement and understand both Simple and Multiple Linear Regression models using the housing dataset, and evaluate their performance using standard regression metrics.

Dataset:
- File: 'Housing.csv'
- Records: 545 entries
- Features: 13 columns (both numerical and categorical)

Key Columns:
- 'price': Target variable (House price)
- 'area', 'bedrooms', 'bathrooms', 'stories', 'parking': Numerical features
- 'mainroad', 'guestroom', 'basement', 'hotwaterheating', 'airconditioning', 'prefarea', 'furnishingstatus': Categorical features

 Libraries Used
- 'pandas'
- 'numpy'
- 'scikit-learn'
- 'matplotlib'

 Workflow

1. Data Loading and Preprocessing
   - Loaded the dataset using pandas.
   - Performed one-hot encoding on categorical variables to make them usable in regression models.

2. Splitting the Data
   - Used 'train_test_split' to divide the data into training and test sets (80-20 split).

3. Model Training
   - Trained a 'LinearRegression' model using the training set.

4. Model Evaluation
   - Metrics used: 
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R-squared (R²)
   - Printed metrics and interpreted model coefficients.

5. Visualization
   - Plotted a simple linear regression line for 'area' vs 'price' using 'matplotlib'.

 Example Output
MAE : 710324.42
MSE : 788978425113.82
R² : 0.6825

 Files Included
- 'Housing.csv': Dataset used for modeling.
- 'TASK3.ipynb': Jupyter notebook with the full code, analysis, and visualizations.
- 'README.md': This file.
