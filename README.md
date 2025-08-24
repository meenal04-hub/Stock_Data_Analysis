# 📈 MAANG Stock Data Analysis & Forecasting

## 🔹 Introduction
This project focuses on analyzing and forecasting the stock performance of **MAANG companies** – **Microsoft, Amazon, Apple, Netflix, and Google**.  
The dataset spans from 2001 to 2023 and includes stock prices (`Open`, `High`, `Low`, `Close`, `Adj Close`) and trading `Volume`.  
The goal of this project is to extract meaningful insights from the stock trends and forecast future stock prices using machine learning and deep learning models.

---

## 🔹 Problem Statement
Stock price prediction is a challenging task due to market volatility and external influencing factors.  
In this project, the objective is:
1. To study and compare the stock performance of MAANG companies.  
2. To perform **time-series forecasting** using different models.  
3. To evaluate and compare the performance of traditional statistical models vs. deep learning models.  

---

## 🔹 Methodology
The project is divided into the following steps:

### 1. Data Collection
- Historical stock data for each company was collected in CSV format.  
- A new column `Company` was added to differentiate records.

### 2. Data Preprocessing
- Combined all datasets into a single DataFrame.  
- Checked for missing values (none found).  
- Converted `Date` column into datetime format.  
- Sorted data chronologically.  

### 3. Exploratory Data Analysis (EDA)
- **Stock Trend Analysis**: Plotted daily `Close` prices to study growth.  
- **Volume Analysis**: Compared trading activity across companies.  
- **Moving Averages**: Calculated 50-day and 200-day moving averages.  
- **Correlation Analysis**: Heatmap to understand relationships between companies.  

### 4. Modeling & Forecasting
The following forecasting models were implemented:
- **ARIMA** – Traditional time-series forecasting.  
- **SARIMA** – Seasonal ARIMA for capturing seasonality.  
- **Prophet** – Captures trend + seasonality effectively.  
- **LSTM (Recurrent Neural Network)** – Deep learning model for sequential data.  

### 5. Model Evaluation
- Models were evaluated using:  
  - **RMSE** (Root Mean Squared Error)  
  - **MAPE** (Mean Absolute Percentage Error)  
- Actual vs Predicted plots were created for visual inspection.  

---

## 🔹 Results & Insights

### 📊 Exploratory Insights
- **Apple** and **Amazon** showed the strongest long-term growth in stock prices.  
- **Netflix** exhibited higher volatility compared to other companies.  
- **Google** and **Microsoft** showed consistent growth with moderate volatility.  
- Trading **Volume** was significantly higher for Amazon compared to others.  

### 📊 Forecasting Results
| Model   | Strengths | Limitations | Best Use Case |
|---------|-----------|-------------|---------------|
| **ARIMA** | Good for short-term predictions | Fails with seasonality and long data | Short-term trend forecasting |
| **SARIMA** | Captures seasonality better | Complex parameter tuning | Seasonal trend forecasting |
| **Prophet** | Handles seasonality + trend well, easy to use | Less accurate for highly volatile stocks | Medium-term forecasts |
| **LSTM** | Best at capturing long-term patterns | Requires large data & computation | Long-term forecasting |

- **LSTM** gave the **lowest RMSE** and was most accurate overall.  
- **Prophet** performed surprisingly well with simpler implementation.  
- Traditional models (ARIMA/SARIMA) worked but were less effective on volatile data like Netflix.  

---

## 🔹 Conclusion
- MAANG stocks show strong growth trends over the past two decades.  
- **Deep learning (LSTM)** outperformed traditional statistical models in long-term forecasting.  
- **Prophet** is a good trade-off between accuracy and simplicity.  
- Investors can use moving averages and volatility analysis to make better-informed decisions.  

---

## 🔹 Future Work
- Integrate **real-time stock data** via APIs.  
- Perform **sentiment analysis** on financial news & Twitter to enhance forecasting.  
- Deploy a **dashboard** for interactive stock trend and prediction visualization.  

---

## 🔹 Author
👩‍💻 **Meenal Gaikwad**
