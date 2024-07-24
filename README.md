# PRODIGY_DS_01
# Diwali Sales Data Analysis

This repository contains a detailed analysis of Diwali sales data. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization to identify patterns and trends in the sales data.

## Table of Contents

- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
  - [Handling Missing Values](#handling-missing-values)
  - [Converting Data Types](#converting-data-types)
  - [Removing Duplicates](#removing-duplicates)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Summary Statistics](#summary-statistics)
  - [Data Visualization](#data-visualization)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used in this analysis contains sales data for Diwali, including information about the products sold, sales amount, customer demographics, and purchase details.

## Data Cleaning

### Handling Missing Values

- Missing values in the dataset are handled appropriately to ensure data integrity and accuracy in analysis.

### Converting Data Types

- Necessary data type conversions are performed to facilitate analysis, such as converting dates to datetime objects and categorical variables to numerical codes.

### Removing Duplicates

- Duplicate rows, if any, are removed from the dataset to avoid skewing the analysis results.

## Exploratory Data Analysis (EDA)

### Summary Statistics

Summary statistics are provided to give an overview of the dataset, including measures such as mean, median, and standard deviation.

### Data Visualization

Several visualizations are created to explore the relationships between variables:

- Distribution of Sales Amount
- Sales by Product Category
- Sales by Region
- Customer Demographics and Sales
- Sales Trends over Time

## How to Run

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/diwali-sales-analysis.git
    cd diwali-sales-analysis
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the analysis script:
    ```sh
    python analysis.py
    ```

## Dependencies

- pandas
- matplotlib
- seaborn

You can install the dependencies using the command `pip install -r requirements.txt`.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
