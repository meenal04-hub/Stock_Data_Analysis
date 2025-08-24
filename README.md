# 📈 MAANG Stock Analysis & Forecasting

This project focuses on analyzing and forecasting the stock prices of **MAANG companies** (Microsoft, Amazon, Apple, Netflix, Google).  
The dataset consists of historical stock data (2001–2023) collected for each company, merged into a single DataFrame for analysis, visualization, and predictive modeling.

---

## 🚀 Project Workflow
1. **Data Collection**
   - Imported CSV files for each company (`Microsoft.csv`, `Amazon.csv`, `Apple.csv`, `Netflix.csv`, `Google.csv`).
   - Combined all datasets into a single DataFrame with an additional `Company` column.

2. **Data Preprocessing**
   - Checked for missing values (none found).
   - Converted `Date` column to datetime format.
   - Sorted data by `Date` for each company.
   - Handled data consistency and formatting.

3. **Exploratory Data Analysis (EDA)**
   - Price trends visualization (Open, High, Low, Close, Adj Close).
   - Volume analysis.
   - Company-wise stock performance comparison.
   - Correlation heatmaps for financial insights.

4. **Modeling & Forecasting**
   - Implemented multiple forecasting models:
     - **ARIMA**
     - **SARIMA**
     - **Facebook Prophet**
     - **LSTM (Deep Learning)**
   - Evaluated models using RMSE, MAPE, and visualization of actual vs predicted trends.

5. **Dashboard (Optional)**
   - Built an interactive dashboard using **Plotly Dash** to visualize stock performance and forecasts dynamically.

---

## 📂 Project Structure
