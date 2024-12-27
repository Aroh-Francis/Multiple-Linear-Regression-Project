MULTIPLE LINEAR REGRESSION

Overview

This project demonstrates the implementation of Multiple Linear Regression using Python. It covers various steps including data loading, cleaning, visualization, feature selection, model training, evaluation, and residual analysis. The dataset used contains economic indicators to predict an index price.

Installation

Before running the code, ensure you have the following Python libraries installed:

pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

Project Structure

1. Data Preparation

Load the Dataset: Reads a CSV file (economic_index.csv) containing economic indicators.

Data Cleaning: Drops unnecessary columns and checks for missing values.

2. Exploratory Data Analysis (EDA)

Pairplot: Visualizes relationships between features.

Correlation Matrix: Analyzes feature relationships.

Scatter Plots: Highlights specific relationships such as interest rate vs unemployment rate.

3. Feature Engineering

Splits data into dependent (Y) and independent (X) variables.

Performs a train-test split (75%-25%).

4. Data Standardization

Standardizes the features using StandardScaler from scikit-learn.

5. Model Training

Implements Linear Regression using LinearRegression.

6. Cross-Validation

Evaluates model performance using cross_val_score.

7. Model Evaluation

Calculates performance metrics:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R2 Score

Adjusted R2 Score

8. Residual Analysis

Plots residual distributions and residual scatter plots.

9. Ordinary Least Squares (OLS)

Performs OLS regression using statsmodels to validate coefficients and intercepts.

Key Visualizations

Pairplot for feature relationships.

Scatter plots to analyze variable relationships.

Residual distribution plots to validate assumptions.

How to Run

Place the dataset (economic_index.csv) in the same directory as the script.

Run the Python script in your preferred IDE or Jupyter Notebook.

View the outputs including metrics, visualizations, and summaries.

Results and Insights

The script predicts the index price based on economic indicators such as interest and unemployment rates.

Provides an evaluation of model performance using metrics like R2 and adjusted R2 scores.

Residual analysis confirms the assumptions of linear regression.

Dependencies

pandas: For data manipulation.

numpy: For numerical computations.

matplotlib: For data visualization.

seaborn: For advanced visualization.

scikit-learn: For machine learning algorithms and preprocessing.

statsmodels: For statistical modeling and analysis.

License

This project is released under the MIT License.

Author

Francis Aroh 