>> Project Overview

This project focuses on cleaning, analyzing, and visualizing agricultural data collected from multiple farms. The goal is to uncover insights about crop yields, resource usage (fertilizer, pesticide, water), and farming practices across various seasons, soil types, and irrigation methods.


>> Data Cleaning

The data cleaning process involved:

Handling missing values using median/mode imputation. Converting columns to appropriate data types. Detecting and capping outliers in numerical features like yield and water usage. Ensuring consistency in categorical variables.


>> Data Visualization

The analysis includes a series of plots to visualize relationships and patterns in the data:

Distribution plots for farm area and yield. Scatter plots to explore relationships between fertilizer, water usage, and yield. Boxplots to compare yield and water usage across crop types, irrigation methods, and soil types. Heatmap showing correlation between numerical features. Grouped bar charts comparing average yields across different seasons and crop types.


>> Key Insights

Certain crop types show significantly higher yields with optimized fertilizer and irrigation. Water usage patterns vary by irrigation method and soil type. Seasonal differences affect crop yield more in specific soil conditions.


>> How to Run

Clone or download this repository.
Open the Jupyter notebook
Ensure your CSV file is in the same directory.
Run all cells to perform data cleaning and see visualizations.


>> Requirements

Python 3.x
Libraries --- pandas, numpy, matplotlib, seaborn
Install with --- pip install pandas numpy matplotlib seaborn
