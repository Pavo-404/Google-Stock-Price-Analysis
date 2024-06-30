# Google-Stock-Price-Analysis

This repository contains a comprehensive analysis of Google's stock prices over the past year. Using Python and various data visualization libraries, this project explores and visualizes the stock data to provide insights into its performance.

Table of Contents
Introduction
Data Collection
Visualizations
Requirements
Installation
Usage
Results
Contributing
License
Introduction
This project aims to analyze Google's stock prices using data collected from Yahoo Finance. The analysis includes various visualizations such as candlestick charts, bar charts, and line charts with interactive features to provide a detailed view of stock performance over time.

Data Collection
The data is collected using the yfinance library, which fetches historical stock prices. The analysis covers the following aspects:

Opening, high, low, and closing prices
Adjusted close prices
Trading volume
Visualizations
The project includes several types of visualizations to represent the stock data:

Candlestick Chart: Shows the opening, high, low, and closing prices.
Bar Chart: Displays the closing prices over time.
Line Chart with Rangeslider: Provides an interactive view with a rangeslider.
Line Chart with Time Period Selectors: Features buttons for selecting different time frames.
Scatter Plot with Hidden Weekend Gaps: Hides gaps for weekends to show a continuous view of trading days.
Requirements
Python 3.7+
pandas
yfinance
plotly
Installation
Clone the repository:
sh
Copy code
git clone https://github.com/yourusername/google-stock-analysis.git
Navigate to the project directory:
sh
Copy code
cd google-stock-analysis
Install the required packages:
sh
Copy code
pip install -r requirements.txt
Usage
Run the Jupyter notebook to fetch data and generate visualizations:
sh
Copy code
jupyter notebook Google\ stock\ analysis.ipynb
Execute the cells in the notebook to see the analysis and visualizations.
Results
The visualizations provide insights into Google's stock performance, including trends, price movements, and trading volumes. These insights can help in making informed investment decisions.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.
