# Human Trafficking Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) of a dataset related to human trafficking. The EDA covers various aspects of data preprocessing, visualization, and analysis to gain insights into the dataset.

## Overview

Human trafficking is a complex issue that affects people worldwide. This EDA aims to better understand and visualize the data related to human trafficking victims.

## Data Sources

- The main dataset is loaded from the file `CTDCK_data.csv`. It contains information about human trafficking cases, including various attributes such as citizenship, means of control, and more.

- Additionally, data related to ISO-3 country codes is used for geographical mapping. This information is sourced from the file `continents2.csv`.

## Data Preprocessing

The following steps are taken to prepare the data for analysis:

1. **Data Loading**: The main dataset and ISO-3 country code dataset are loaded using the Pandas library.

2. **Column Removal**: The first column, which contains all null values, is removed from the main dataset.

3. **Merging ISO-3 Codes**: ISO-3 country codes are merged with the main dataset to facilitate geographical analysis.

4. **Duplicate Removal**: Duplicate rows in the dataset are removed to ensure data integrity.

## Data Exploration

The EDA includes the following data exploration and visualization steps:

1. **Data Summary**: Basic information about the dataset, including data types and missing values, is displayed.

2. **Unique Value Counts**: The number of unique values in each categorical column (excluding specific columns) is visualized using a bar chart.

3. **Year of Registration**: A bar chart shows the distribution of human trafficking cases over the years.

4. **Age Distribution**: Another bar chart illustrates the age distribution of victims.

5. **Majority-Related Columns**: Bar charts are used to visualize data from columns starting with 'majority'.

6. **Geographical Analysis**: Choropleth maps are created to show the origin (citizenship) and exploitation locations of human trafficking victims.

7. **Binary Variable Correlation**: A heatmap is generated to visualize the correlation between binary variables in the dataset.

## Conclusion

This EDA provides a comprehensive overview of the human trafficking dataset, enabling insights into various aspects of this critical issue. Further analysis and modeling can be built upon this foundation to address human trafficking more effectively.

## Getting Started

To use this project, follow these steps:

1. Clone the repository to your local machine:

2. Install the required libraries specified in the Jupyter Notebook.

3. Run the Jupyter Notebook `Human Trafficing EDA.ipynb` to perform data exploration and analysis.

4. Modify the code or dataset as needed for your specific use case.

## Dependencies

- pandas
- matplotlib
- plotly
- seaborn


## License

This project is licensed under the MIT License 

