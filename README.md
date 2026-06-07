# Walmart Sales Forecasting & Risk Analytics

## Project Overview

This project analyzes Walmart sales data to uncover business insights, forecast future sales, and identify factors affecting revenue performance. The project combines Exploratory Data Analysis (EDA), Machine Learning, Time Series Analysis, and Risk Analytics to support data-driven business decisions.

---

## Business Problem

Retail businesses need accurate sales forecasting to improve inventory management, promotional planning, and overall business performance. The objective of this project is to:

- Forecast future weekly sales.
- Identify key factors influencing sales.
- Analyze the impact of economic indicators on revenue.
- Detect revenue risks and low-performing periods.
- Generate actionable recommendations to increase future sales.

---

## Dataset Information

The dataset contains 6,435 records and includes the following features:

- Store
- Date
- Weekly_Sales
- Holiday_Flag
- Temperature
- Fuel_Price
- CPI
- Unemployment

---

## Project Workflow

### Data Preprocessing
- Checked missing values and data quality.
- Converted Date column into datetime format.
- Created new features such as Year, Month, and Week.
- Prepared data for machine learning models.

### Exploratory Data Analysis (EDA)
- Sales trend analysis.
- Store-wise performance analysis.
- Holiday vs Non-Holiday sales comparison.
- Correlation analysis.
- Economic indicator impact analysis.

### Feature Engineering
Created additional features:
- Year
- Month
- Week

### Machine Learning

#### Regression Model
Objective:
Predict future weekly sales.

Algorithm Used:
- Random Forest Regressor

Evaluation Metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

#### Classification Model
Objective:
Classify High Sales and Low Sales periods.

Algorithm Used:
- Random Forest Classifier

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1 Score

### Time Series Analysis
- Weekly sales trend analysis.
- Moving Average analysis.
- ARIMA forecasting.
- Future sales prediction.

### Risk Analytics
- Revenue Risk Analysis.
- Holiday Dependency Analysis.
- Economic Risk Analysis.
- Store Performance Risk Analysis.
- Demand Forecasting Risk Analysis.

---

## Key Insights

- Holiday weeks generated significantly higher sales than regular weeks.
- Store performance was one of the strongest drivers of revenue.
- CPI and Unemployment affected customer purchasing behavior.
- Economic indicators influenced overall sales trends.
- Sales forecasting identified future demand patterns.
- Feature importance analysis revealed key business drivers.

---

## Business Recommendations

- Increase inventory during holiday periods.
- Focus marketing efforts on high-performing stores.
- Monitor economic indicators for better planning.
- Use forecasting models for inventory optimization.
- Implement targeted campaigns during low-sales periods.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Statsmodels (ARIMA)
- Jupyter Notebook

---

## Project Outcomes

- Built an end-to-end Machine Learning solution for sales forecasting.
- Applied Predictive Analytics and Time Series Analysis.
- Conducted Risk Analytics using economic indicators.
- Generated business insights to support revenue growth.
- Improved decision-making through data-driven recommendations.

---

## Author

**Manvendra Kumar**

Aspiring Data Scientist | Data Analyst | Machine Learning Enthusiast
