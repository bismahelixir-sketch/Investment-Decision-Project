# Capital Investment Decision Support Tool

## About the Project

I started this project to learn how data science can be used to support real business decisions.

The idea is to build a tool that helps users evaluate whether a company should invest in a new project by analyzing historical financial data and estimating possible future outcomes.

The tool is meant to support decision-making by presenting useful insights, not by making the final decision for the user.

---

## Planned Features

- Import a company's historical financial data
- Forecast future financial performance
- Calculate investment metrics such as NPV, IRR, and Payback Period
- Run different scenarios to see how changes in assumptions affect the results
- Display the results in an interactive dashboard

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Plotly
- yfinance

---

## Project Status

This project is currently under development.

I'm building it step by step while learning more about financial analysis, forecasting, and data science.

### Data Collection

* Downloaded five years of historical stock data using the yFinance library.
* Collected datasets for Apple, Microsoft, and Nvidia.
* Stored the original datasets inside the `data/raw` folder.

### Data Cleaning

* Checked dataset structure, column names, and data types.
* Converted the Date column into datetime format.
* Verified that the datasets contain no missing values or duplicate records.
* Saved the cleaned dataset in the `data/processed` folder.

### Exploratory Data Analysis

* Generated summary statistics using Pandas.
* Created the first time-series visualization of Apple's closing stock price using Matplotlib.
* Improved the visualization by adding titles, labels, gridlines, and formatting.
* Analyzed long-term trends, short-term fluctuations, and significant price movements.
* Practiced distinguishing observations from possible explanations by recognizing that market events require additional evidence before drawing conclusions.


---

## Author

Bismah Ahmed
