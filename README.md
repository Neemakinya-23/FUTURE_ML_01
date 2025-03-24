# ☕ Coffee Shop Sales Forecasting

## Project Overview
This project focuses on **time series forecasting** to predict coffee shop sales using **Facebook Prophet**. The goal is to analyze past sales data, identify trends and seasonality, and generate reliable forecasts to help in business decision-making.

## Objectives
- Develop a **time series forecasting model** for predicting future sales.
- Analyze **trends, seasonality, and patterns** in the coffee shop's sales data.
- Compare **actual vs. predicted sales** to evaluate model performance.
- Provide **visualizations** to interpret forecast accuracy.

##  Tools & Technologies
- **Python** (for data processing & modeling)
- **Facebook Prophet** (for time series forecasting)
- **Scikit-learn** (for baseline comparisons)
- **Pandas & NumPy** (for data manipulation)
- **Matplotlib & Seaborn** (for visualization)

##  Dataset
- **Source:**  coffee shop’s historical sales data from Kaggle.
- **Granularity:** Daily sales records.
- **Features:** 
  - `ds` (Date of sales)
  - `y` (Total sales)

## Methodology
1. **Data Preprocessing:**
   - Cleaned and formatted the dataset (`ds` as datetime, `y` as numerical sales).
   - Handled missing values (if any).
   
2. **Model Training:**
   - Split the dataset into **train (80%)** and **test (20%)**.
   - Trained **Facebook Prophet** on the historical sales data.

3. **Forecasting & Evaluation:**
   - Generated **future sales predictions**.
   - Compared **actual vs. predicted** values for evaluation.
   - Plotted **trend analysis & seasonality effects**.

##  Results & Insights
- The model successfully captured **overall sales trends** and **seasonality**.
- The **actual vs. predicted sales** plot showed that Prophet provides **reasonably accurate** predictions but has slight variations due to demand fluctuations.
- Seasonal patterns were evident in the data, influencing coffee sales.

##  Visualizations
1. **Forecast Plot:** Displays predicted sales with uncertainty intervals.
2. **Actual vs. Predicted Plot:** Helps assess the model's accuracy.
3. **Seasonality Trends:** Shows how sales change over time.

##  Key Learnings
- **Prophet** is powerful for time series forecasting but may require **fine-tuning**.
- **Data quality & granularity** significantly impact forecasting performance.
- Including **external factors** (weather, holidays, promotions) can improve prediction accuracy.

##  Future Improvement
- Try **other forecasting models** (LSTM, ARIMA) for comparison.
- Optimize Prophet parameters for better accuracy.

  ## 📊 Model Predictions
Below is a visualization of the actual vs. predicted sales:

![Model Predictions](Model%20prediction.png)


