# Supermarket Sales Trend Analysis
Business Data Management Capstone Project – IIT Madras

---

## Project Overview

This project presents a comprehensive analysis of supermarket sales trends using historical data from three branches in Myanmar (Yangon, Naypyitaw, Mandalay) covering January to March 2019. The analysis addresses key business challenges such as maximizing profit margins, optimizing inventory, understanding customer satisfaction, and forecasting demand. The findings provide actionable recommendations to enhance operational efficiency, customer satisfaction, and profitability for supermarket chains operating in competitive retail environments.

---

## Dataset Description
- **Source**: [Supermarket Sales Data by Aung Pyae](supermarket_sales_original.csv) (originally from Kaggle, now removed)
- **Coverage**: January 2019 – March 2019, 3 branches in Myanmar
- **Size**: 1000 rows × 17 columns
- **Features**:
  - **Transactional**: Invoice ID, Branch, City, Date, Time
  - **Product**: Product Line, Unit Price, Quantity, COGS, Gross Income, Gross Margin %
  - **Customer**: Customer Type, Gender, Payment Method, Rating (1–10 scale)

---

## Methodology
- **Data Cleaning & Preparation**: Standardized date formats, checked for duplicates, handled inconsistencies using Python and Excel.
- **Descriptive Analytics**: Explored sales, profit, and customer ratings by product line, branch, and payment method.
- **Pareto Analysis**: Identified revenue distribution across products and customers.
- **Customer Feedback Analysis**: Compared average ratings by product line and branch.
- **Trend Analysis**: Assessed monthly and daily sales/profit trends and seasonal patterns.
- **Forecasting**: Used ARIMA and SARIMA models to predict future sales and identify seasonality

---

## Acknowledgments
- Data Source: Aung Pyae (Kaggle)
- Institution: IIT Madras, BS Degree Program
- Tools: Python, Excel, VS Code, Google Colab