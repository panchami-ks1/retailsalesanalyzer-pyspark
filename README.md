

# Retail Sales Analyzer using PySpark

This project implements a retail sales analysis tool using PySpark to explore and familiarize with data engineering concepts. It covers various aspects such as data loading, cleaning, analysis, and visualization of sales data.

## Project Overview

The **Retail Sales Analyzer** executes the following tasks:

1. **Data Loading**: Reads retail sales data from a CSV file into a Pandas DataFrame.
2. **Data Cleaning**: Identifies and removes rows containing missing values.
3. **Data Manipulation and Analysis**:
    - Calculates total sales for each product.
    - Identifies the best-selling product.
    - Computes average daily sales.
4. **Visualization**:
    - Plots sales trends over time.
    - Displays sales per product using bar charts.
5. **Class Implementation**:
    - The `RetailSalesAnalyzer` class encapsulates methods for data loading, cleaning, analysis, and visualization.
6. **Script Execution**: A script is provided to instantiate `RetailSalesAnalyzer`, execute its methods, and output the analysis results.

## Features

- **Data Cleaning**: Ensures the dataset is free from missing values.
- **Sales Analysis**: Provides key insights like total sales per product, best-selling items, and daily sales trends.
- **Visualization**: Uses Matplotlib to generate informative charts for better understanding of the sales data.

## Technologies Used

- **PySpark**: For distributed data processing.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating visualizations.
- **Python 3.x**: For scripting and implementing the `RetailSalesAnalyzer` class.



## Getting Started

### Prerequisites

Ensure that you have Python 3.x and PySpark installed on your machine.

You can install the necessary Python packages by running:

```bash
pip install -r requirements.txt
```

### Running the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/panchami-ks1/retailsalesanalyzer-pyspark.git
   cd retailsalesanalyzer-pyspark
   ```

2. **Prepare Data**:
    - Place your sales data (CSV format) into the current directory.
    - Modify the script to point to your CSV file if necessary.



   The script will:
    - Load the sales data.
    - Perform data cleaning.
    - Analyze sales per product and calculate statistics.
    - Generate visualizations such as bar charts and line plots.

## Example Visualizations

- **Sales Trends**: Line chart showing sales over time.
- **Sales per Product**: Bar chart showing total sales for each product.

