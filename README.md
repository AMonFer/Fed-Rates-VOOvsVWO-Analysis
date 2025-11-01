# FED Interest Rate Impact Analysis: S&P 500 (VOO) vs. Emerging Markets (VWO)

This repository contains the complete data analysis project, from data collection in Python to the final dashboard built in Power BI.

---

## 📊 Final Power BI Dashboard

This dashboard visualizes the project's key findings, comparing market sensitivities to the Federal Reserve's interest rate policies.

![Power BI Dashboard Preview](Dash.png)

---

## 🎯 Project Objective

The primary goal of this analysis was to test the hypothesis that Emerging Markets (VWO) are more sensitive to Federal Reserve interest rate changes than the U.S. market (VOO) during the 2010-2025 period.

---

## 🛠️ Tools & Technologies

* **Python:** Used for data collection (via FRED and yfinance APIs) and data transformation (Pandas).
* **Power BI:** Used for data modeling, analysis, and building the final dashboard.
* **Google Colab:** Served as the development environment for all Python scripting.

---

## 📈 Key Conclusions

1.  **Hypothesis Confirmed:** The period-based analysis validates that Emerging Markets (VWO) exhibit a **greater negative sensitivity** to Fed policy during tightening and cutting cycles (Periods 2 & 3).
2.  **Key Finding (Period 4):** The strong positive correlation during the 2022+ rate-hike cycle suggests the market was not reacting negatively to high rates, but **positively to a strong, resilient economy** (a "soft landing") that could withstand them.

---

## 📂 Repository Files

* **[VOOvsVWO.ipynb]**: The Google Colab notebook containing all Python code for data collection, cleaning, and transformation.
* **[fed_market_timeseries.csv]**: The clean, final time-series dataset used as the source for the Power BI dashboard.
* **[fed_market_correlations.csv]**: A pivot csv to show the correlations between the interest rates and markets
