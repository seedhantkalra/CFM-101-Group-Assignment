# Automated Financial Portfolio Generator

## Overview

This project is an Automated Financial Portfolio Generator that allows users to create and evaluate investment portfolios. The tool uses historical stock data to generate portfolios based on user-defined criteria and filters. It also leverages multithreading to improve time efficiency when processing large datasets.

## Features

- **Data Extraction:** Fetches historical stock data using the Yahoo Finance API.
- **Data Filtering:** Filters out invalid or undesirable stocks based on specific criteria.
- **Portfolio Generation:** Automatically creates a portfolio of stocks that meet the criteria.
- **Financial Calculations:** Uses financial functions to assess the viability and performance of the generated portfolio.
- **Visualization:** Provides visual representations of the portfolio's performance over time.

## Installation

### Prerequisites

Ensure you have Python 3.x installed on your system. The required Python libraries include `pandas`, `numpy`, `numpy-financial`, `yfinance`, and `matplotlib`.

### Clone the Repository

You can clone the repository from GitHub and navigate to the project directory.

## Usage

1. **Set the Parameters:**
   Modify the `start_date` and `end_date` variables in the script to specify the time period for the stock data.

2. **Run the Script:**
   Execute the script using Python.

3. **View the Results:**
   The script will output the generated portfolio along with visualizations of its performance.

## Code Structure

- **Data Extraction:** The script uses `yfinance` to fetch historical stock data and stores it in a Pandas DataFrame for further processing.
- **Data Filtering:** The code filters out stocks that do not meet certain criteria such as price and volume. Multithreading is implemented to speed up the filtering process.
- **Portfolio Generation:** Valid stocks are used to create a portfolio, and financial metrics are calculated to assess the portfolio's performance.
- **Visualization:** `matplotlib` is used to create graphs that visualize the portfolio's performance.

## Example

An example usage involves setting specific start and end dates for the stock data, running the script, and analyzing the generated portfolio's performance metrics and visualizations.
