# QCTO-Project

# Avocado Sales and Pricing Dataset (2015-2023) - README

## Project Title:
**Exploring Trends in Avocado Sales and Pricing (2015-2023)**

---

## Overview:

This project aims to analyze the sales and pricing trends of Hass avocados across different regions in the United States between 2015 and 2023. The dataset provides comprehensive information about avocado sales volumes, average prices, and regional data, allowing for a detailed exploration of consumer behavior and market trends in the avocado industry.

---

## Dataset Information:

- **Source**: Hass Avocado Board
- **Time Period**: 2015 - 2023
- **Number of Rows**: 23,035 (or based on the final cleaned dataset)
- **Number of Columns**: 14 (or based on the final cleaned dataset)

---

## Columns and Data Types:

1. **Date**: The date of the recorded data point (Categorical - Date)
2. **AveragePrice**: The average price of a single avocado (Numerical - Float)
3. **Total Volume**: The total volume of avocados sold (Numerical - Float)
4. **4046**: Total sales of small avocado PLU 4046 (Numerical - Float)
5. **4225**: Total sales of large avocado PLU 4225 (Numerical - Float)
6. **4770**: Total sales of extra-large avocado PLU 4770 (Numerical - Float)
7. **Total Bags**: The total number of avocado bags sold (Numerical - Float)
8. **Small Bags**: Total number of small bags sold (Numerical - Float)
9. **Large Bags**: Total number of large bags sold (Numerical - Float)
10. **XLarge Bags**: Total number of extra-large bags sold (Numerical - Float)
11. **Type**: Conventional or organic avocados (Categorical - Object)
12. **Region**: Region where the data was collected (Categorical - Object)
13. **Year**: Year of the data point (Numerical - Int)
14. **Month**: Month of the data point (Numerical - Int)

---

## Data Collection:

The dataset was sourced from the **Hass Avocado Board**, which tracks the volume and prices of avocado sales in different regions. The data is organized by region, avocado type (conventional or organic), and contains specific price points and sales volumes for different avocado sizes.

The dataset was downloaded from publicly available repositories and compiled into a CSV file. The analysis was performed using Python, utilizing libraries like Pandas, Matplotlib, and Seaborn for data manipulation, exploration, and visualization.

---

## Project Objectives:

1. **Explore Trends**:
   - Analyze how avocado prices have fluctuated over time.
   - Identify patterns in sales volumes across different regions.
   - Compare conventional vs. organic avocado sales and pricing.

2. **Detect Seasonality**:
   - Identify any seasonal effects on pricing and sales.
   - Understand regional variations in demand and price fluctuations.

3. **Uncover Insights**:
   - Correlate sales volumes with price changes to uncover market dynamics.
   - Visualize sales data to identify key periods of growth or decline in avocado consumption.

---

## Data Cleaning and Preparation:

- Handled missing values by imputing mode for categorical variables and mean for numerical variables.
- Checked and resolved issues with column names and data types.
- Removed outliers and anomalies where necessary using statistical methods and visualization techniques.

---

## Visualizations and Insights:

The dataset was explored using various visualization techniques:
- **Histograms** to visualize the distribution of `AveragePrice` and `Total Volume`.
- **Box plots** to detect outliers in pricing data.
- **Scatter plots** to understand relationships between sales volume and pricing.
- **Correlation matrix and heatmap** to reveal correlations between numerical variables like price, volume, and bag types.

---


---

## License:

This dataset is publicly available and may be used for educational, analytical, and research purposes. Please credit the **Hass Avocado Board** as the source of the dataset if used in publications or reports.

---

## Contact Information:

For any questions or feedback, feel free to contact:

- **Name**: Jamie Hamann
- **Email**: jamiehamann3@gmail.com

---

## Conclusion:

This project provides a deep dive into avocado sales and pricing trends across various U.S. regions. By exploring the data through statistical summaries, visualizations, and potential predictive modeling, we gain insights into consumer behavior and market dynamics within the avocado industry.

--- 
