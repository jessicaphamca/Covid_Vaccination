# Covid_Vaccination
COVID-19 has impacted the life of everyone today, and we are still in the battle with the pandemic for more than a year now. As we are adjusting to the new normal, scientists are working day and night to develop the best anti-vaccine to the COVID-19 virus. However, once the vaccine was out, many people had a lot of second-thoughts on whether the vaccination will be 100% effective or not. The below analysis of the COVID-19 data includes a detailed analysis of the vaccination data from each country and whether or not people are getting vaccinated to prevent the infection of Coronavirus.
## Data Wrangling Summary

### Problem Description
The analysis aims to explore the relationships between vaccination rates, coronavirus cases, GDP, and life expectancy. The goal is to clean and combine various datasets, handle missing data, and prepare them for correlation analysis.

### The Data
- **Main Data**: Vaccination and coronavirus data.
- **Supplemental Data**: GDP and life expectancy data.

### Data Wrangling Steps

#### 1. Read in the Data
The datasets were loaded into the environment for further processing.

#### 2. Getting to Know the Data
Exploratory data analysis (EDA) was conducted to understand the structure, data types, and distributions. This helped identify missing values and potential inconsistencies.

#### 3. Data Preparation
The preparation process involved cleaning and standardizing each dataset.

- **Vaccination Data**:
  - **Missing Values**: Identified and handled missing values using appropriate imputation techniques.
  - **Rename Columns**: Renamed columns for clarity and consistency.
  
- **Coronavirus Data**:
  - **Missing Values**: Handled missing values similarly.
  - **Rename Columns**: Renamed columns to ensure consistency across datasets.

- **GDP Data**:
  - **Missing Values**: Dealt with missing GDP data using interpolation or other imputation methods.
  - **Rename Columns**: Renamed columns to align with other datasets.

- **Life Expectancy Data**:
  - **Missing Values**: Filled missing values where necessary.
  - **Rename Columns**: Renamed columns for uniformity.

#### 4. Getting Ready to Combine the Datasets
- Merged the two main datasets (vaccination and coronavirus data).
- Merged the two supplemental datasets (GDP and life expectancy data).
- Standardized column names across all datasets.

#### 5. Combine the Datasets
All datasets were combined into one unified dataset.
- **Missing Values**: Remaining missing values were addressed after the merge.

#### 6. Analysis
- Correlation analysis was conducted to find relationships between the variables (e.g., vaccination rates, COVID-19 cases, GDP, and life expectancy).

### Find Correlations
- **Correlation Plots**: Plotted both positive and negative correlations.
- **Positive Correlations Plot**: Highlighted relationships where increases in one variable corresponded with increases in another.
- **Negative Correlations Plot**: Showed where increases in one variable corresponded with decreases in another.
- **Correlations Analysis**: Analyzed the significant relationships and their implications.

### Conclusion
This analysis helped identify important correlations between vaccination rates, coronavirus impact, economic factors, and life expectancy. The cleaned and combined datasets enabled deeper insights into the interactions between public health and socio-economic conditions.



## Jupyter Notebook

[View the notebook on GitHub](https://github.com/jessicaphamca/Covid_Vaccination/blob/main/Project_Covid_Vaccination.ipynb)
