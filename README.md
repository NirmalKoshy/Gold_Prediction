# Project Overview
This project involves analyzing a comprehensive dataset of daily gold prices obtained from Nasdaq, spanning from January 19, 2014, to January 22, 2024. The dataset includes key financial metrics such as opening and closing prices, daily highest and lowest prices, and trading volume. The primary goal is to explore historical trends, identify patterns, and gain insights into the behavior of the gold market over this decade. By applying statistical analysis and machine learning techniques, the project aims to uncover relationships within the data, forecast future gold prices, and provide valuable insights for investors and analysts. This analysis serves as a resource for understanding market dynamics and making informed investment decisions based on data-driven insights.

Throughout the project we have performed the following steps: -

**Imported Necessary Libraries:** We started by importing essential libraries for data manipulation (Pandas, NumPy), visualization (Matplotlib, Seaborn, Plotly), and modeling (Scikit-learn, Prophet).

**Loaded and Explored Data:** After loading the dataset, we explored it by calculating summary statistics like mean, median, and standard deviation for the Close, Volume, Open, High, and Low columns. This gave us an idea of the distribution and trends in the gold prices.

**Data Cleaning:** We checked for missing values and confirmed that the dataset was clean, with no missing data, which allowed us to proceed with analysis without any imputation steps.

**Feature Engineering and Preprocessing:** We planned to scale the data using MinMaxScaler to normalize the feature values, ensuring that all the input variables are on a similar scale, which is important for machine learning models.

**Prediction Models:** We implemented and prepared different models for prediction, including:

1) Random Forest Regressor: To capture non-linear relationships and patterns in gold price movements.

2) Linear Regression: For a baseline comparison with a simpler model.

3) Prophet Model: Specifically for time-series forecasting, which is well-suited for making future predictions based on past data trends.

**Performance Evaluation:** We planned to evaluate model performance using metrics like Mean Squared Error (MSE), R-squared (R²), and Mean Absolute Percentage Error (MAPE), to understand how well our models are predicting the future prices.
