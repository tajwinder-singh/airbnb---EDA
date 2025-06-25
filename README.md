# Exploratory Data Analysis on Airbnb Listings

## Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on Airbnb listings dataset. The goal is to understand the structure of the data, clean it, visualize key variables, and derive insights to support business decisions and future model development.

## Dataset Description
The dataset contains information about Airbnb property listings, including host details, location, pricing, availability, and other listing attributes.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Steps Performed

### 1. Data Inspection
- Checked null values, data types, and dataset shape.
- Basic statistical summary using `.describe()`.

### 2. Data Cleaning
- Removed irrelevant columns such as `name`, `house_rules`, and `license`.
- Handled missing values and ensured column consistency.

### 3. Visualizations
- **Room Type Distribution:** Countplot showing most common types of rooms (e.g., Entire home, Private room).
- **Price Distribution:** Histogram to detect skewness and outliers in pricing.
- **Availability Analysis:** Bar plot of `availability_365` to find listing availability trends.
- **Neighbourhood Insights:** Visuals showing which areas have more listings.
- **Minimum Nights Distribution:** Boxplot to identify common booking durations and outliers.
- **Correlation Bar plot:** To identify relationships among numerical features.

### 4. Key Insights
- Entire homes are the most listed properties.
- Some listings have extremely high prices, indicating potential outliers.
- Few properties are available all year round.
- Certain neighborhoods have higher concentrations of listings.

## Conclusion
This EDA highlights data inconsistencies, pricing patterns, and listing behaviors that can guide hosts and Airbnb in strategic decisions. The dataset is now ready for modeling or dashboard creation.

## Author
Tajwinder (Taj) Singh

## To view the notebook with outputs, open it in nbviewer
