# Financial Inclusion Data Analysis Project

## Overview
This project analyzes global financial inclusion data to identify key socioeconomic factors behind disparities in financial access across countries. We used data from the Global Findex Database, published by the World Bank, covering 140 countries over four years (2011, 2014, 2017, 2021).

## Motivation
Understanding financial inclusion rates and their influencing factors is crucial for policymakers, financial institutions, and organizations working towards inclusive economic growth. This project aims to uncover patterns and insights that can inform decision-making and shape strategies for promoting financial inclusion.

## Data and Methods

### Data Source
- Global Findex Database (World Bank)
- Over 1000 indicators on topics such as account ownership, card usage, saving, internet access, phone ownership, and financial resilience

### Tools and Techniques
1. Data Preprocessing:
   - R programming language
   - Packages: readxl, countrycode

2. Exploratory Data Analysis:
   - Correlation analysis
   - Summary statistics
   - Data visualization using ggplot2

3. Machine Learning Models:
   - K-Nearest Neighbors (KNN)
   - Decision Tree

## Key Findings

1. Global account ownership increased by 50% from 2011 to 2021, with 76% of adults having an account at a bank or regulated institution in 2021.

2. Significant disparities in financial inclusion rates based on Gross National Income (GNI) per capita and geographical regions:
   - High-income economies show higher rates of account ownership and card usage compared to low-income economies.
   - Africa lags behind other continents in most financial inclusion indicators.

3. Strong positive correlation between account ownership, financial institution account ownership, credit/debit card ownership, and card usage.

4. The United States, as a high-income economy, shows consistently high percentages across all analyzed indicators.

5. Machine Learning Results:
   - KNN model accuracy ranged from 66.67% to 86.21% depending on the specific income group or continent.
   - Decision Tree model performed better overall in classifying countries based on income groups and continents.

## Conclusions
While the analysis revealed important trends and disparities in financial inclusion, the complexity of the dataset and presence of missing data posed challenges for achieving high accuracy with machine learning models. Currently, data analysis provides a more reliable method for identifying trends and patterns in financial inclusion rates. Further research and improved data collection are needed to enhance the predictive capabilities of machine learning models in this domain.

## Future Work
- Explore more advanced machine learning techniques
- Incorporate additional socioeconomic factors
- Analyze time series data to identify long-term trends
- Investigate country-specific case studies for successful financial inclusion initiatives
