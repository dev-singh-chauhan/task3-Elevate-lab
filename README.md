# task3-Elevate-lab

# House Price Prediction

This notebook demonstrates a simple linear regression model to predict house prices based on features like average area income and average area house age.

## Data

The dataset used is loaded from `/content/archive.zip`. It's assumed to contain columns such as 'Avg. Area Income', 'Avg. Area House Age', and 'Avg. Area Number of Rooms' Basically a data set which have been provided by Elevate lab from Kaggle.

## Methodology

1. **Data Loading and Preprocessing:** The dataset is loaded using pandas. Missing values are checked.
2. **Feature Selection:** 'Avg. Area Income' and 'Avg. Area House Age' are selected as features (X), and 'Avg. Area Number of Rooms' is the target variable (y).
3. **Model Training:** The data is split into training and testing sets. A Linear Regression model is trained on the training data.
4. **Model Evaluation:** The model's performance is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).
5. **Visualization:** A scatter plot is created to visualize the actual vs. predicted values.

## Usage

1. Upload the dataset (`archive.zip`) to your Colab environment.
2. Run all the code cells in the notebook.
3. Observe the model's performance metrics and the visualization.

## Dependencies

- pandas
- matplotlib
- scikit-learn (sklearn)
