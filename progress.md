# Progress Log

## Progress

### Day 1 – Project Setup

* Set up the project structure and organized folders for data, notebooks, source code, and reports.
* Created a Python virtual environment and connected the project to GitHub.
* Added a README file to document the project and track progress.

### Day 2 – Data Collection

* Used the `yfinance` library to download five years of historical stock data for Apple, Microsoft, and Nvidia.
* Saved the original datasets in the `data/raw` folder to keep a clean copy of the downloaded data.
* Learned how to collect financial data programmatically instead of downloading it manually.

### Day 3 – Data Exploration & Cleaning

* Explored the datasets using pandas to understand their structure and contents.
* Used `head()`, `tail()`, `shape`, `columns`, and `info()` to inspect the data.
* Checked for missing values and duplicate records to make sure the datasets were ready for analysis.
* Converted the `Date` column to the `datetime` data type for future time-series analysis.
* Saved the cleaned datasets in the `data/processed` folder while keeping the original raw data unchanged.
* Learned why data validation and keeping separate raw and processed datasets are important steps in a data science project.

### Day 4 - Exploratory Data Analysis

* Collected five years of historical stock data for Apple, Microsoft, and Nvidia.
* Cleaned and validated the datasets by checking data types, missing values, and duplicate records.
* Completed initial exploratory data analysis using Apple as the baseline dataset.
* Generated summary statistics and built the first stock price visualization using Matplotlib.

### Day 5 – Return & Volatility Analysis

* Calculated daily percentage returns from historical closing prices using vectorized Pandas operations.
* Applied the `shift(1)` function to align each trading day with the previous day's closing price for return calculations.
* Performed descriptive statistical analysis of daily returns, including mean, standard deviation, minimum, and maximum values.
* Interpreted daily return statistics to evaluate average performance and short-term price volatility.
* Visualized daily return patterns over time to identify periods of increased market volatility and significant price movements.

### Day 6 – Multi-Company Stock Analysis
Compared the historical stock prices of Apple, Microsoft, and NVIDIA using a single visualization.
Calculated daily returns for all three companies.
Compared daily return patterns to evaluate differences in volatility.
Observed that NVIDIA had larger daily price fluctuations, while Apple and Microsoft showed relatively more stable movements.
