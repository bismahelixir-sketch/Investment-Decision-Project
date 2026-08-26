# Progress Log

## Progress

### ✅ Day 1 – Project Setup

* Set up the project structure and organized folders for data, notebooks, source code, and reports.
* Created a Python virtual environment and connected the project to GitHub.
* Added a README file to document the project and track progress.

### ✅ Day 2 – Data Collection

* Used the `yfinance` library to download five years of historical stock data for Apple, Microsoft, and Nvidia.
* Saved the original datasets in the `data/raw` folder to keep a clean copy of the downloaded data.
* Learned how to collect financial data programmatically instead of downloading it manually.

### ✅ Day 3 – Data Exploration & Cleaning

* Explored the datasets using pandas to understand their structure and contents.
* Used `head()`, `tail()`, `shape`, `columns`, and `info()` to inspect the data.
* Checked for missing values and duplicate records to make sure the datasets were ready for analysis.
* Converted the `Date` column to the `datetime` data type for future time-series analysis.
* Saved the cleaned datasets in the `data/processed` folder while keeping the original raw data unchanged.
* Learned why data validation and keeping separate raw and processed datasets are important steps in a data science project.
