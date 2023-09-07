# Exploratory Data Analysis (EDA) with Earthquake Data

In the realm of data analysis and machine learning, it is essential to embark on a journey of data exploration and understanding before applying sophisticated algorithms. This process is known as Exploratory Data Analysis (EDA) and forms the foundation for making informed decisions, building predictive models, and uncovering valuable insights from datasets.

## Dataset Used

https://www.kaggle.com/datasets/alessandrolobello/the-ultimate-earthquake-dataset-from-1990-2023

## Libraries and Tools

Before delving into the data analysis, we need to set up our environment and import the necessary libraries and tools. These include:

- **Pandas**: For data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Plotly**: A powerful library for interactive visualizations.
- **Missingno**: For visualizing missing data.
- **WordCloud**: For generating word clouds.
- **Scikit-Learn**: For machine learning tasks.
- **Google Colab**: To upload and work with data in a Google Colab environment.

## Data Loading and Initial Exploration

The first step is to load our earthquake dataset from a CSV file, assuming it's named 'Earthquakes-1990-2023.csv.' We display the initial few rows, check its shape, list column names, and generate summary statistics for both numerical and categorical columns.

We also examine data types and look for missing values within the dataset, ensuring a solid understanding of its structure.

## Data Preprocessing

Data preprocessing is crucial to ensure the data is in a usable format for analysis. Key preprocessing steps in this code include:

- Identifying and removing duplicate rows to avoid redundancy.
- Converting date and time columns into the appropriate datetime format.
- Filtering earthquake data based on specific criteria, such as magnitude or location (e.g., California, Alaska, Nevada, and Washington).
- Transforming date columns into additional features like hour, day of the month, weekday, month, month name, and year.

## Exploratory Data Analysis (EDA)

The core of this code is dedicated to EDA, where we explore and visualize various aspects of the earthquake data:

- **Magnitude Analysis**: We analyze earthquake magnitudes over time, by hour, and in specific regions.
- **Temporal Trends**: We investigate how earthquake occurrences and magnitudes vary by year, month, and day of the month.
- **Top Locations**: We identify the top earthquake locations and visualize their distribution.
- **Data Types and Statuses**: We examine the distribution of earthquake data types and statuses.

## Correlation Analysis

To gain insights into what factors might be correlated with earthquake magnitudes, we calculate the correlation matrix between numerical features and visualize it as a heatmap. Additionally, we identify the top features most positively and negatively correlated with earthquake magnitudes.
