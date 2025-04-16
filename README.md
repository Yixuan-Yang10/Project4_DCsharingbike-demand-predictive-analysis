# Project4_DCsharingbike-demand-predictive-analysis
# 🚲 Bike Sharing Demand Forecasting in Washington DC (2011–2018)

## 📋 Project Overview

This project analyzes daily bike-sharing customer data in the **Washington, D.C. metro area** from **January 1, 2011 to December 31, 2018**, alongside weather information. The objective is to forecast customer demand to help avoid **oversupply or shortage** of shared bikes and understand key factors influencing bike usage.

---

## 🧹 Data Cleaning & Preparation

We used **R** and **Excel** to clean and prepare the dataset:

- Handled missing values and inconsistent entries
- Recoded categorical variables as binary variables
- Extracted 365 observations as hold-out samples for validation(using SAS), etc

---

## 📊 Exploratory Data Analysis

Using **SAS**, we conducted an exploratory analysis and identified:

- A clear **seasonal pattern** in bike demand
- An overall **increasing trend** over time

---

## ⏱️ Time Series Modeling

We applied both **univariate** and **multivariate** time series forecasting techniques in SAS:

### 🔹 Univariate Models:
- **Seasonal Dummies + Linear Trend**
- **Log Seasonal Dummies + First Trend Difference + MA(2)**
- **Cyclical trend model + error model**
- **ARIMA model + Regression Holiday**

### 🔹 Multivariate Models:
- **Regression Models with All Predictions + error model**
  
### 🔹 Cross-correlation analysis with weather features

---

## ✅ Key Findings

- **Temperature**, **fog**, and **holidays** were the most significant variables influencing bike demand.

---

## 📈 Business Insights

- To **prevent oversupply**, especially during low-demand months, a forecast was made for the coming month.
- Based on the model, we recommend **limiting supply to around 4,000 bikes/day** next month.

---

## 🛠️ Tools & Technologies Used

- **SAS**: Time series modeling, ARIMA fitting, and cross-correlation
- **R**: Data cleaning
- **Excel**: Initial preprocessing and variable inspection


