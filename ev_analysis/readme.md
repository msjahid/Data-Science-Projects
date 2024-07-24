# Delaware EV Charging Stations and Rebates

📊 This dataset provides comprehensive information on electric vehicle (EV) charging stations and associated rebates in Delaware. By analyzing attributes such as award number, location details, charging station brand, cost, and rebate amounts, this project aims to uncover trends and insights into the deployment and incentivization of EV infrastructure in the state.

## Introduction

This project focuses on the analysis of EV charging stations and rebates awarded in Delaware. The dataset contains detailed information about each rebate award, including location, brand, cost, and rebate amount. The goal is to explore the distribution and financial aspects of EV charging stations to understand how rebates are utilized and their impact on EV infrastructure development.

## Dataset Description

The dataset comprises several columns capturing various details about each rebate award. Each row represents an individual rebate award with the following columns:

1. **Award Number**: Unique identifier for each rebate award.
2. **Month**: Month when the rebate was awarded.
3. **Year**: Year when the rebate was awarded.
4. **City**: City where the charging station is located.
5. **Zip**: ZIP code of the location of the charging station.
6. **Charging Station Brand**: Brand or manufacturer of the charging station.
7. **County**: County where the charging station is located.
8. **Cost of Charging Station**: Cost of the charging station.
9. **Rebate Amount**: Amount of rebate awarded for the charging station.

### Sample Data

| award_number | month | year | city       | zip   | charging_station_brand | county     | cost_of_charging_station | rebate_amount |
| ------------ | ----- | ---- | ---------- | ----- | ---------------------- | ---------- | ------------------------ | ------------- |
| RCS0618102   | 6     | 2018 | Hockessin  | 19707 | Tesla                  | New Castle | 500.0                    | 250.0         |
| RCS0618103   | 6     | 2018 | Wilmington | 19802 | AeroVironment          | New Castle | 649.0                    | 324.5         |
| RCS0618104   | 6     | 2018 | Middletown | 19709 | ChargePoint            | New Castle | 674.0                    | 337.0         |
| RCS0618105   | 6     | 2018 | Bear       | 19701 | Tesla                  | New Castle | 500.0                    | 250.0         |
| RCS0618106   | 6     | 2018 | Bear       | 19701 | Clipper Creek          | New Castle | 589.0                    | 294.5         |

## Data Quality

The dataset is clean and well-structured, making it suitable for analysis. The data provides a reliable basis for exploring the patterns and effectiveness of rebate programs for EV charging stations in Delaware.

## Analysis

The analysis will focus on:

1. **Rebate Distribution**: Examining how rebates are distributed across different cities and counties.
2. **Cost vs. Rebate**: Analyzing the relationship between the cost of charging stations and the rebate amounts.
3. **Brand Insights**: Investigating the prevalence of different charging station brands and their associated costs and rebates.
4. **Temporal Trends**: Exploring how rebate awards vary over time (monthly and yearly).

## Exploratory Data Analysis

### Count of Missing Values

![Count of Missing Values](ev_charts/Count%20of%20Missing%20Values.png)

### Distribution of Charging Station

![Distribution of Charging Station](ev_charts/Distribution%20of%20Charging%20Station.png)
![KDE- Distribution of Charging Station](ev_charts/KDE-%20Distribution%20of%20Charging%20Station.pngg)

### Analysis of County Distribution

![Analysis of County Distribution](ev_charts/Analysis%20of%20County%20Distribution.png)

### City Charging Station Availability Overview

![City Charging Station Availability Overview](ev_charts/City%20Charging%20Station%20Availability%20Overview.png)

### Charging Station Brand Distribution

![Charging Station Brand Distribution](ev_charts/Charging%20Station%20Brand%20Distribution.png)

### Charging Station Costs by County and Season

![Charging Station Costs by County and Season](ev_charts/Charging%20Station%20Costs%20by%20County%20and%20Season.png)

### Monthly Charging Cost

![Monthly Charging Cost](ev_charts/Monthly%20Charging%20Cost.png)

### Lineplot, Pointplot, and Barplot of Yearly Charging Cost

![Lineplot, Pointplot, and Barplot of Yearly Charging Cost](ev_charts/Lineplot,%20Pointplot,%20and%20Barplot%20of%20Yearly%20Charging%20Cost.png)

### Charging Station Costs by season in County wise

![Charging Station Costs by season in New Castle](ev_charts/Charging%20Station%20Costs%20by%20season%20in%20New%20Castle.png)

![Charging Station Costs by season in Sussex](ev_charts/Charging%20Station%20Costs%20by%20season%20in%20Sussex.png)

![Charging Station Costs by season in Kent](ev_charts/Charging%20Station%20Costs%20by%20season%20in%20Kent.png)

### Charging Station Costs by Season and County

![Charging Station Costs by Season and County](ev_charts/Charging%20Station%20Costs%20by%20Season%20and%20County.png)

### Rebate Amount by County & Season

![Rebate Amount by County & Season](ev_charts/Rebate%20Amount%20by%20County%20&%20Season.png)

### Monthly Rebate Amount

![Monthly Rebate Amount](ev_charts/Monthly%20Rebate%20Amount.png)

### Lineplot, Pointplot, and Barplot of Yearly Rebate Amount

![Lineplot, Pointplot, and Barplot of Yearly Rebate Amount](ev_charts/Lineplot,%20Pointplot,%20and%20Barplot%20of%20Yearly%20Rebate%20Amount.png)

### Rebate Amount by season in County wise

![Rebate Amount by season in New Castle](ev_charts/Rebate%20Amount%20by%20season%20in%20New%20Castle.png)

![Rebate Amount by season in Sussex](ev_charts/Rebate%20Amount%20by%20season%20in%20Sussex.png)

![Rebate Amount by season in Kent](ev_charts/Rebate%20Amount%20by%20season%20in%20Kent.png)

### Rebate Amount by Season and County

![Rebate Amount by Season and County](ev_charts/Rebate%20Amount%20by%20Season%20and%20County.png)

## How to Use This Repository

1. **Clone the Repository**: `git clone https://github.com/yourusername/ev_analysis.git`
2. **Navigate to the Project Directory**: `cd ev_analysis`
3. **Explore the Data**: The dataset is available in the `ev_data` folder. Load and explore it using your preferred data analysis tools.
4. **Run the Analysis**: Use the provided Jupyter notebooks to perform analyses and visualize the findings.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## Contact

If you have any questions or suggestions, please feel free to contact me at [ms_jahid@yahoo.com].
