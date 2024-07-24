# Smartphone Insights: Exploratory Data Analysis

📱 This project delves into the dynamic world of smartphones through exploratory data analysis (EDA). By examining a dataset with various attributes such as brand, model, price, specifications, and features, we aim to uncover trends and insights that drive the smartphone market.

## Introduction

This project focuses on analyzing a comprehensive dataset of smartphones, exploring various attributes such as brand, model, price, specifications, and features. The goal is to identify patterns, trends, and insights that can help understand the smartphone market and inform consumer and business decisions.

## Dataset Description

The dataset comprises 937 rows and 26 columns, each representing a different attribute of the smartphones. The columns in the dataset are as follows:

1. **Brand Name**: The name of the smartphone brand.
2. **Model**: The model name of the smartphone.
3. **Price**: The price of the smartphone.
4. **Rating**: The rating of the smartphone, typically based on user reviews or expert evaluations.
5. **Has 5G**: Indicates whether the smartphone has 5G connectivity capability.
6. **Has NFC**: Indicates whether the smartphone has Near Field Communication (NFC) technology.
7. **Has IR Blaster**: Indicates whether the smartphone has an Infrared (IR) blaster for remote control functionality.
8. **Processor Brand**: The brand of the processor used in the smartphone.
9. **Num Cores**: The number of cores in the smartphone processor.
10. **Processor Speed**: The speed of the smartphone processor.
11. **Battery Capacity**: The capacity of the smartphone battery, usually measured in milliampere-hours (mAh).
12. **Fast Charging Available**: Indicates whether the smartphone supports fast charging technology.
13. **Fast Charging**: Details about the fast charging capability, such as the type of fast charging technology.
14. **RAM Capacity**: The amount of Random Access Memory (RAM) in the smartphone, usually measured in gigabytes (GB).
15. **Internal Memory**: The internal storage capacity of the smartphone, usually measured in gigabytes (GB) or terabytes (TB).
16. **Screen Size**: The size of the smartphone screen, typically measured diagonally in inches.
17. **Refresh Rate**: The screen refresh rate, usually measured in Hertz (Hz).
18. **Num Rear Cameras**: The number of rear cameras on the smartphone.
19. **Num Front Cameras**: The number of front cameras on the smartphone.
20. **OS**: The operating system of the smartphone.
21. **Primary Camera Rear**: The resolution of the primary rear camera.
22. **Primary Camera Front**: The resolution of the primary front camera.
23. **Extended Memory Available**: Indicates whether the smartphone supports extended memory.
24. **Extended Upto**: The maximum capacity of extended memory supported, usually measured in gigabytes (GB).
25. **Resolution Width**: The width of the screen resolution.
26. **Resolution Height**: The height of the screen resolution.

## Data Quality

The dataset is mostly clean but contains some missing values in certain columns. Below is a summary of the missing values:

- **Rating**: 101 missing values
- **Processor Brand**: 20 missing values
- **Num Cores**: 6 missing values
- **Processor Speed**: 42 missing values
- **Battery Capacity**: 11 missing values
- **Fast Charging**: 211 missing values
- **Num Front Cameras**: 4 missing values
- **OS**: 14 missing values
- **Primary Camera Front**: 5 missing values
- **Extended Upto**: 480 missing values

The dataset contains no duplicate values, ensuring reliability and accuracy for analysis.

## Analysis

The analysis will focus on:

1. **Brand and Model Analysis**: Examining the distribution of brands and models.
2. **Price Analysis**: Exploring the price range and factors influencing smartphone prices.
3. **Feature Analysis**: Investigating the prevalence of features such as 5G, NFC, IR blaster, and fast charging.
4. **Performance Analysis**: Analyzing processor specifications, RAM, and battery capacity.
5. **Camera Analysis**: Exploring the camera specifications and their impact on ratings and prices.
6. **Missing Value Handling**: Addressing missing values to ensure data integrity for analysis.

### Exploratory Data Analysis

### Distribution of every columns

![Distribution of every columns](smartphone_charts/Distribution%20of%20every%20columns.png)

### Most Available of Processor Brand

![Most Available of Processor Brand](smartphone_charts/Most%20Available%20of%20Processor%20Brand.png)

### Distribution of Operating Systems & Fast Charging Availability

![Distribution of Operating Systems & Fast Charging Availability](smartphone_charts/Distribution%20of%20Operating%20Systems%20&%20Fast%20Charging%20Availability.png)

### Most Available Brand Name

![Most Available Brand Name](smartphone_charts/Most%20Available%20Brand%20Name.png)

### Distribution of Has NFC, 5G, and IR Blaster

![Distribution of Has NFC, 5G, and IR Blaster](smartphone_charts/Distribution%20of%20Has%20NFC,%205G,%20and%20IR%20Blaster.png)

### Correlation Heat Map of different Mobile Features

![Correlation Heat Map of different Mobile Features](smartphone_charts/Correlation%20Heat%20Map%20of%20different%20Mobile%20Features.png)

### Primary Camera vs Front Camera

![Primary Camera vs Front Camera](smartphone_charts/Primary%20Camera%20vs%20Front%20Camera.png)

### Brand Name vs Rating

![Brand Name vs Rating](smartphone_charts/Brand%20Name%20vs%20Rating.png)

### Processor Brand vs Price

![Processor Brand vs Price](smartphone_charts/Processor%20Brand%20vs%20Price.png)

### Processor Brand vs Refresh Rate

![Processor Brand vs Refresh Rate](smartphone_charts/Processor%20Brand%20vs%20Refresh%20Rate.png)

### Brand Name vs RAM Capacity

![Brand Name vs RAM Capacity](smartphone_charts/Brand%20Name%20vs%20RAM%20Capacity.png)

### Brand Name vs Internal Memory

![Brand Name vs Internal Memory](smartphone_charts/Brand%20Name%20vs%20Internal%20Memory.png)

## How to Use This Repository

1. **Clone the Repository**: `git clone https://github.com/msjahid/smartphone_eda.git`
2. **Navigate to the Project Directory**: `cd smartphone_eda`
3. **Explore the Data**: The dataset is available in the `smartphone_data` folder. Load and explore it using your preferred data analysis tools.
4. **Run the Analysis**: Use the provided Jupyter notebooks to perform analyses and visualize the findings.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## Contact

If you have any questions or suggestions, please feel free to contact me at [ms_jahid@yahoo.com].
