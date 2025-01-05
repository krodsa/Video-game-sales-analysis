# Video-game-sales-analysis

This project analyzes historical video game sales data to uncover trends, derive insights, and predict future sales. The dataset used for this analysis is sourced from Kaggle.

Project Overview

The purpose of this project is to:

- Perform data cleaning and preprocessing to prepare the dataset for analysis.
- Conduct exploratory data analysis (EDA) to identify key patterns and trends.
- Derive descriptive statistics and actionable insights from the data.
- Predict future sales using a simple linear regression model.

Dataset Description

The dataset contains video game sales data, including attributes like:

- Name: The name of the game.
- Platform: The console or platform the game was released on.
- Year: The release year of the game.
- Genre: The game's genre.
- Global and Regional Sales: Sales figures in North America, Europe, Japan, and other regions.

Methodology

1. Data Cleaning and Preprocessing:

- Dropped rows with missing values to ensure consistency.
- Created a new column, Total_Sales, by summing up regional sales figures.
- Filtered out invalid or missing release years.

2. Exploratory Data Analysis (EDA):

- Identified the top-performing platforms by total sales.
- Visualized global sales trends over time.
- Summarized regional sales contributions.

3. Descriptive Statistics and Insights:

- Calculated the average sales per game and identified the top-selling game.
- Summarized the sales distribution across different regions.

4. Predictive Analysis:

- Built a linear regression model to predict future global sales.
- Evaluated the model's performance using the R-squared metric.
- Generated sales forecasts for the years 2021–2025.

Key Findings

- Top Platforms: Consoles like PS2, Xbox 360, and Wii dominated total sales, reflecting their popularity and market share.
- Global Trends: Sales peaked around 2008–2009, driven by major game releases and console launches. Sales declined in subsequent years.
- Regional Insights: North America and Europe accounted for the largest share of sales, while Japan contributed significantly but at a smaller scale.
- Predicted Sales: The regression model forecasts stable sales growth through 2025, assuming no major industry disruptions.

Insights and Next Steps

This analysis provides a foundation for understanding historical sales trends and regional preferences in the gaming industry. Potential next steps include:

- Extending the analysis to include correlations with economic or demographic data.
- Enhancing the prediction model with more sophisticated techniques like time-series forecasting.
- Visualizing additional insights using tools like Tableau.

Acknowledgments

- Dataset sourced from Kaggle.
- Libraries used: pandas, numpy, matplotlib, scikit-learn.
