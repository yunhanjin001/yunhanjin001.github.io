---
title: "StockGambleDetect"
excerpt: "a specialized tool designed to identify speculative gambling behaviors <br/><img src='/images/portfolio_stock_gamble.png'>"
collection: portfolio
---

This portfolio highlights the [StockGambleDetect](https://github.com/yunhanjin001/StockGambleDetect) project, a specialized tool designed to identify speculative gambling behaviors in the stock market using machine learning.

-----

## Project Portfolio: StockGambleDetect

**Project Overview**
[StockGambleDetect](https://github.com/yunhanjin001/StockGambleDetect) is a Python-based quantitative analysis framework. It leverages machine learning to distinguish between standard value-based market fluctuations and high-risk, speculative trading patterns. By analyzing historical data, the project provides a data-driven approach to market risk assessment.

### Technical Stack

  * **Languages:** Python (57.6%), Jupyter Notebook (42.4%)
  * **Core Algorithm:** Random Forest Classifier (implemented in [`forest_template.py`](https://www.google.com/search?q=%5Bhttps://github.com/yunhanjin001/StockGambleDetect/blob/main/forest_template.py%5D\(https://github.com/yunhanjin001/StockGambleDetect/blob/main/forest_template.py\)))
  * **Data Handling:** Pandas, NumPy, and Openpyxl for Excel integration.
  * **Data Source:** Structured financial datasets (e.g., [`gamble.xlsx`](https://www.google.com/search?q=%5Bhttps://github.com/yunhanjin001/StockGambleDetect/blob/main/gamble.xlsx%5D\(https://github.com/yunhanjin001/StockGambleDetect/blob/main/gamble.xlsx\))).

-----

### Key Functional Modules

#### 1\. Data Engineering & Preprocessing ([`calculate_data.ipynb`](https://www.google.com/search?q=%5Bhttps://github.com/yunhanjin001/StockGambleDetect/blob/main/calculate_data.ipynb%5D\(https://github.com/yunhanjin001/StockGambleDetect/blob/main/calculate_data.ipynb\)))

  * **Feature Extraction:** Extracts behavioral indicators such as volatility spikes, abnormal turnover rates, and non-linear price movements.
  * **Data Pipeline:** Cleans and transforms raw financial records into a standardized format suitable for supervised learning.

#### 2\. Machine Learning Implementation ([`forest_template.py`](https://www.google.com/search?q=%5Bhttps://github.com/yunhanjin001/StockGambleDetect/blob/main/forest_template.py%5D\(https://github.com/yunhanjin001/StockGambleDetect/blob/main/forest_template.py\)))

  * **Model Training:** Uses a Random Forest ensemble to handle high-dimensional financial features.
  * **Behavioral Classification:** Categorizes stock performance into "Gambling-type" vs. "Non-gambling-type" based on learned historical patterns.
  * **Feature Importance:** Evaluates which market factors contribute most significantly to speculative bubbles.

#### 3\. Execution & Result Generation ([`scsj.py`](https://www.google.com/search?q=%5Bhttps://github.com/yunhanjin001/StockGambleDetect/blob/main/scsj.py%5D\(https://github.com/yunhanjin001/StockGambleDetect/blob/main/scsj.py\)))

  * **Automated Analysis:** A script designed to run the end-to-end pipeline—from reading input data to exporting predictions.
  * **Organized Outputs:** Results are systematically stored in the [`result`](https://www.google.com/search?q=%5Bhttps://github.com/yunhanjin001/StockGambleDetect/tree/main/result%5D\(https://github.com/yunhanjin001/StockGambleDetect/tree/main/result\)) directory for further review and backtesting.

-----

### Impact & Insights

  * **Behavioral Finance Lens:** Moves beyond traditional technical analysis by focusing on investor psychology and "gambling" footprints.
  * **Extensibility:** The project is modularly designed with separate [`data`](https://www.google.com/search?q=%5Bhttps://github.com/yunhanjin001/StockGambleDetect/tree/main/data%5D\(https://github.com/yunhanjin001/StockGambleDetect/tree/main/data\)) and code folders, making it easy to adapt for different global markets.
  * **Risk Mitigation:** Provides a foundational tool for institutional or individual investors to screen for stocks with excessive speculative heat.

-----

### Developer Reflection

In this project, I addressed the challenge of noisy financial data by implementing robust feature engineering and an ensemble learning approach. This work demonstrates my proficiency in Python for finance and my ability to translate complex behavioral theories into actionable code.

> **View Source:** [yunhanjin001/StockGambleDetect](https://github.com/yunhanjin001/StockGambleDetect)