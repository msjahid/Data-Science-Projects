# Global Deep Dive: AI, ML, & Data Science Salaries

💼 Explore the landscape of AI, ML, and Data Science salaries globally with this comprehensive analysis. This project investigates salaries across various roles, experience levels, and locations to reveal trends and insights in the data science and machine learning job markets.

## Introduction

This project focuses on analyzing a dataset of salaries for AI, ML, and Data Science roles. By examining various attributes such as experience level, employment type, job title, and location, the analysis aims to uncover trends, disparities, and insights in the global job market for these fields.

## Dataset Description

The dataset comprises 20,565 rows and 11 columns, each representing different attributes related to job salaries. The columns in the dataset are:

1. **work_year**: The year in which the salary was recorded.
2. **experience_level**: The experience level of the employee (e.g., SE for Senior, MI for Mid-Level).
3. **employment_type**: The type of employment (e.g., FT for Full-Time).
4. **job_title**: The job title of the employee.
5. **salary**: The salary amount in the specified currency.
6. **salary_currency**: The currency in which the salary is paid (e.g., USD).
7. **salary_in_usd**: The salary amount converted to USD.
8. **employee_residence**: The location where the employee resides.
9. **remote_ratio**: The ratio of remote work, indicating how much of the job is performed remotely.
10. **company_location**: The location of the company.
11. **company_size**: The size of the company (e.g., M for Medium).

### Data Quality

- **Missing Values**: The dataset contains no missing values.
- **Duplicates**: The dataset contains 8,668 duplicate values.
- **RangeIndex**: The dataset includes 20,565 entries.
- **Data Types**: The dataset consists of 4 integer columns and 7 object columns.

## Analysis

The analysis will focus on:

1. **Salary Trends**: Examining salary trends over the years and across different job titles and experience levels.
2. **Experience and Salary**: Investigating the impact of experience level on salary.
3. **Employment Type Analysis**: Exploring salary differences between various employment types.
4. **Location Impact**: Analyzing how employee residence and company location affect salaries.
5. **Remote Work Analysis**: Evaluating the effect of remote work ratio on salary.
6. **Company Size**: Understanding the relationship between company size and salary.

## Exploratory Data Analysis

###

![](ai_salaries_charts)

### Count of Missing Values

![Count of Missing Values](ai_salaries_charts/Count%20of%20Missing%20Values.png)

### Distribution of Salary in USD

![Distribution of Salary in USD](<ai_salaries_charts/Distribution%20of%20Salaries(USD).png>)

![KDE-Distribution of Salary in USD](ai_salaries_charts/KDE-Distribution%20of%20Salary%20in%20USD.png)

### Analysis of Work Year, Experience Level, Employment Type, Company Size, and Remote Ration Distribution

![Analysis of Work Year Distribution](ai_salaries_charts/Analysis%20of%20Work%20Year%20Distribution.png)

![Analysis of Experience Level Distribution](ai_salaries_charts/Analysis%20of%20Experience%20Level%20Distribution.png)

![Analysis of Employment Type Distribution](ai_salaries_charts/Analysis%20of%20Employment%20Type%20Distribution.png)

![Analysis of Company Size Distribution](ai_salaries_charts/Analysis%20of%20Company%20Size%20Distribution.png)

![Analysis of Remote Ration Distribution](ai_salaries_charts/Analysis%20of%20Remote%20Ration%20Distribution.png)

### Distribution of Salary Currency Overview

![Distribution of Salary Currency Overview](ai_salaries_charts/Distribution%20of%20Salary%20Currency%20Overview.png)

### Distribution of Company Location Overview (Top 20)

![Distribution of Company Location Overview (Top 20)](<ai_salaries_charts/Distribution%20of%20Company%20Location%20Overview%20(Top%2020).png>)

### Distribution of Job Role Overview (Top 20)

![Distribution of Job Role Overview (Top 20)](<ai_salaries_charts/Distribution%20of%20Job%20Role%20Overview%20(Top%2020).png>)

### Boxplot of Salary

![Boxplot of Salary](ai_salaries_charts/Boxplot%20of%20Salary.png)

### Most Job Role Available

![Most Job Role Available](ai_salaries_charts/Most%20Job%20Role%20Available.png)

### Top Paid Job Titles in Tech Industry

![Top Paid Job Titles in Tech Industry](ai_salaries_charts/Top%20Paid%20Job%20Titles%20in%20Tech%20Industry.png)

### Bar plot for average salary by experience level and company size

![Bar plot for average salary by experience level and company size](ai_salaries_charts/Bar%20plot%20for%20average%20salary%20by%20experience%20level%20and%20company%20size.png)

### Bar plot for average salary by remote ratio and experience level

![Bar plot for average salary by remote ratio and experience level](ai_salaries_charts/Bar%20plot%20for%20average%20salary%20by%20remote%20ratio%20and%20experience%20level.png)

### Salary Trends over Years

![Salary Trends over Years](ai_salaries_charts/Salary%20Trends%20over%20Years.png)

### Work year, Experience level, Employment type, Remote ratio, Company size vs Salary

![Work year, Experience level, Employment type, Remote ratio, Company size vs Salary](ai_salaries_charts/Work%20year,%20Experience%20level,%20Employment%20type,%20Remote%20ratio,%20Company%20size%20vs%20Salary.png)

### Violin plot of Work year, Experience level, Employment type, Remote ratio, and Company size vs Salary

![Violin plot of Work year, Experience level, Employment type, Remote ratio, and Company size vs Salary](ai_salaries_charts/Violin%20plot%20of%20Work%20year,%20Experience%20level,%20Employment%20type,%20Remote%20ratio,%20and%20Company%20size%20vs%20Salary.png)

### Correlation Heat Map of Different Salaries Features

![Correlation Heat Map of Different Salaries Features](ai_salaries_charts/Correlation%20Heat%20Map%20of%20Different%20Salaries%20Features.png)

### Salary Trends: Yearly Analysis by Experience level, Employment type, Remote ratio, and Company size

![Salary Trends: Yearly Analysis by Experience level, Employment type, Remote ratio, and Company size](ai_salaries_charts/Salary%20Trends:%20Yearly%20Analysis%20by%20Experience%20level,%20Employment%20type,%20Remote%20ratio,%20and%20Company%20size.png)

### Pair plot Distribution of Numeric Columns

![Pair plot Distribution of Numeric Columns](ai_salaries_charts/Pair%20plot%20Distribution%20of%20Numeric%20Columns.png)

### Mean salary by country between 2020 and 2024

![Mean salary by country between 2020 and 2024](ai_salaries_charts/Mean%20salary%20by%20country%20between%202020%20and%202024.png)

### Mean salary by company size between 2020 and 2024

![Mean salary by company size between 2020 and 2024](ai_salaries_charts/Mean%20salary%20by%20company%20size%20between%202020%20and%202024.png)

### Mean salary by experience level between 2020 and 2024

![Mean salary by experience level between 2020 and 2024](ai_salaries_charts/Mean%20salary%20by%20experience%20level%20between%202020%20and%202024.png)

### Line plot, Point plot, and Bar Plot of Yearly Salary Overview

![Line plot, Point plot, and Bar Plot of Yearly Salary Overview](ai_salaries_charts/Line%20plot,%20Point%20plot,%20and%20Bar%20Plot%20of%20Yearly%20Salary%20Overview.png)

## How to Use This Repository

1. **Clone the Repository**: `git clone https://github.com/msjahid/ai_salaries.git`
2. **Navigate to the Project Directory**: `cd ai_salaries`
3. **Explore the Data**: The dataset is available in the `data` folder. Load and explore it using your preferred data analysis tools.
4. **Run the Analysis**: Use the provided Jupyter notebooks to perform analyses and visualize the findings.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## Contact

If you have any questions or suggestions, please feel free to contact me at [ms_jahid@yahoo.com].
