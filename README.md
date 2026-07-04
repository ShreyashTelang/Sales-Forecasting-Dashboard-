# Sales-Forecasting-Dashboard-

A predictive analytics project that forecasts future sales using **Meta Prophet (Facebook Prophet)** and visualizes historical and forecasted trends through an interactive **Power BI Dashboard**.

This project demonstrates the complete workflow of **time-series forecasting**, including data preprocessing, model training, evaluation, forecasting future sales, and business intelligence visualization.

---

# Project Overview

Forecasting future sales helps businesses make informed decisions regarding inventory management, budgeting, workforce planning, and marketing strategies.

In this project, historical sales data from the **Superstore Dataset** is used to train a **Prophet** forecasting model, predict future sales, evaluate model performance, and visualize the results using Power BI.

---

# Dataset

Dataset Used:

**Superstore Sales Dataset**

Dataset includes:

- Order Date
- Sales
- Customer Information
- Product Information
- Region
- Category
- Segment

---

# Technologies Used

- Python
- Pandas
- NumPy
- Prophet (Meta Prophet)
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Power BI
- DAX

---

# Project Workflow

```text
Historical Sales Data
        │
        ▼
Data Cleaning
        │
        ▼
Daily Sales Aggregation
        │
        ▼
Prepare Prophet Dataset
        │
        ▼
Train Prophet Model
        │
        ▼
Forecast Future Sales
        │
        ▼
Model Evaluation
        │
        ▼
Export Forecast Results
        │
        ▼
Power BI Dashboard
```

---

# Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Removed missing values
- Converted Order Date to datetime format
- Aggregated sales by date
- Prepared data in Prophet format (`ds`, `y`)

---

# Forecasting Model

Model Used:

**Prophet (Meta Prophet)**

The model was configured with:

- Yearly Seasonality
- Weekly Seasonality
- Automatic Trend Detection
- Future Sales Prediction

---

# Forecasting Results

The model generates:

- Historical Sales
- Forecasted Sales
- Lower Confidence Interval
- Upper Confidence Interval

Future sales were forecasted for the next **90 days**.

---

# Model Evaluation

The forecasting model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

Example:

| Metric | Value |
|---------|-------|
| MAE | 2032.18 |
| RMSE | 2435.95 |

> **Note:** The evaluation metrics shown above are from one model run. They may change if the dataset, forecast horizon, or model parameters are modified.

---

# Power BI Dashboard

The dashboard contains:

### KPI Cards

- Forecast Sales
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

### Visualizations

- Historical vs Forecast Sales
- Future Sales Forecast
- Forecast Confidence Interval
- Monthly Sales Trend
- Forecast Data Table

---

### Interactive Filters

- Year
- Month

---

# Output Files

The Python notebook generates:

```text
sales_forecast.csv
forecast_metrics.csv
```

These files are imported into Power BI for visualization.

---


# Python Libraries Used

```python
pandas
numpy
matplotlib
prophet
scikit-learn
```

Install dependencies:

```bash
pip install pandas numpy matplotlib prophet scikit-learn
```

---

# Business Insights

The forecasting model provides valuable business insights, including:

- Identification of future sales trends.
- Estimation of expected sales over the next 90 days.
- Visualization of confidence intervals to understand prediction uncertainty.
- Support for inventory planning and demand forecasting.
- Assistance in strategic business decision-making through predictive analytics.

---

# Skills Demonstrated

- Time Series Forecasting
- Predictive Analytics
- Data Cleaning
- Data Preprocessing
- Prophet Forecasting
- Python Programming
- Exploratory Data Analysis (EDA)
- Model Evaluation
- Data Visualization
- Power BI Dashboard Development
- Business Intelligence

---

# Future Improvements

- Compare Prophet with ARIMA and SARIMA models.
- Experiment with LSTM neural networks for forecasting.
- Include holidays and promotional events in the model.
- Forecast sales by category and region.
- Deploy the forecasting model as a Streamlit web application.
- Publish the dashboard to Power BI Service with a scheduled refresh.

---

# Author

**Shreyash Telang**

Computer Engineering Student | Aspiring Data Analyst | Machine Learning Enthusiast

## If you found this project useful, consider giving it a star!
