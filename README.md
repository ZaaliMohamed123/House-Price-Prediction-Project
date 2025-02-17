# **House Price Prediction Project**

This project aims to predict house prices based on various features from the California Housing dataset. The workflow includes data exploration, preprocessing, training an XGBoost regression model, evaluating its performance, and using it for predictions.

**Overview of the Process**

1.	Importing Dependencies:
 * Essential libraries such as NumPy, pandas, Matplotlib, Seaborn, and Scikit-learn are imported.
 * The XGBRegressor model from the XGBoost library is used for regression.
2.	Data Collection and Analysis:
 * The California Housing dataset is fetched using fetch_california_housing().
 * The dataset's description and structure are examined.
3.	Exploratory Data Analysis (EDA):
 * Histograms are plotted to visualize the distribution of features.
 * A correlation heatmap is constructed to understand relationships between features.
4.	Data Preprocessing:
 * Features (X) and target variable (Y) are separated.
 * Data standardization is performed using StandardScaler to normalize the feature values.
5.	Model Training:
 * The dataset is split into training and testing sets.
 * An XGBoost regressor (XGBRegressor) is instantiated and trained on the training data.
6.	Model Evaluation:
 * Predictions are made on the training data and evaluated using R-squared (r2_score) and Mean Absolute Error (MAE).
 * Similarly, predictions are made on the test data and evaluated.
7.	Predictive System:
 * A function predict() is defined to take new input data, preprocess it, and predict house prices using the trained model.



