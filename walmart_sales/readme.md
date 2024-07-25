# Walmart Sales Exploration

🛒 Explore the dynamics of Walmart sales with this comprehensive analysis. This project investigates weekly sales across different stores, examining various factors such as holidays, temperature, fuel prices, CPI, and unemployment rates to reveal trends and insights in Walmart's sales performance.

## Introduction

This project focuses on analyzing a dataset of weekly sales for Walmart stores. By examining various attributes such as holidays, temperature, fuel prices, CPI, and unemployment rates, the analysis aims to uncover trends, disparities, and insights in Walmart's sales performance.

## Dataset Description

The dataset comprises 6,435 rows and 8 columns, each representing different attributes related to weekly sales. The columns in the dataset are:

1. **store**: The store number.
2. **date**: The week of sales.
3. **weekly_sales**: Sales for the given store and date.
4. **holiday_flag**: Whether the week is a special holiday week (1) or not (0).
5. **temperature**: Average temperature in the region.
6. **fuel_price**: Cost of fuel in the region.
7. **cpi**: Consumer Price Index.
8. **unemployment**: Unemployment rate in the region.

### Data Quality

- **Missing Values**: The dataset contains no missing values.
- **Duplicates**: The dataset contains no duplicate values.
- **RangeIndex**: The dataset includes 6,435 entries.
- **Data Types**: The dataset consists of 5 float columns, 2 integer columns, and 1 object column.

## Analysis

The analysis will focus on:

1. **Weekly Sales Trends**: Examining sales trends over the weeks and across different stores.
2. **Holiday Impact**: Investigating the impact of holiday weeks on sales.
3. **Temperature Analysis**: Exploring the relationship between temperature and sales.
4. **Fuel Price Analysis**: Analyzing how changes in fuel prices affect sales.
5. **CPI and Sales**: Evaluating the correlation between CPI and sales.
6. **Unemployment Impact**: Understanding the effect of unemployment rates on sales.

## Exploratory Data Analysis

### Distribution of Numerical Information

![Distribution of Numerical Information](walmart_charts/Distribution%20of%20Numerical%20Information.png)

### Correlation Heatmap

![Correlation Heatmap](walmart_charts/Correlation%20Heatmap.png)

### Yearly Season-wise Total Weekly Sales

![Yearly Season-wise Total Weekly Sales](walmart_charts/Yearly%20Season-wise%20Total%20Weekly%20Sales.png)

### Holiday Distribution Over the Years

![Holiday Distribution Over the Years](walmart_charts/Holiday%20Distribution%20Over%20the%20Years.png)

### Distribution of Years

![Distribution of Years](walmart_charts/Distribution%20of%20Years.png)

## How to Use This Repository

1. **Clone the Repository**: `git clone https://github.com/yourusername/walmart_sales.git`
2. **Navigate to the Project Directory**: `cd walmart_sales`
3. **Explore the Data**: The dataset is available in the `walmart_data` folder. Load and explore it using your preferred data analysis tools.
4. **Run the Analysis**: Use the provided Jupyter notebooks to perform analyses and visualize the findings.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## Contact

If you have any questions or suggestions, please feel free to contact me at [ms_jahid@yahoo.com].
