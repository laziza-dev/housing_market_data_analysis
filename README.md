# UK Housing Market Analysis
## Project Overview
This project provides an end-to-end exploratory data analysis (EDA) of UK housing price trends. By cleaning historical market data and visualizing price variations across different property segments, we aim to uncover long-term market behavior and correlations between various housing price indices.

# Methodology
Data Cleaning: Removed features with excessive missing values (>40%) and applied median imputation to numerical columns to ensure statistical robustness.

Outlier Management: Capped extreme price values at the 99th percentile to prevent skewness in our visualizations and analysis.

Feature Processing: Organized the dataset to compare multiple price indices (All, New, Modern, Older) simultaneously.

## Exploratory Data Analysis (EDA) Insights
1. Price Distribution
The histogram visualizes the frequency distribution of housing prices across the dataset.

Insight: The distribution shows how frequently specific price points occur, helping us understand the "typical" market value.

2. Market Trends Over Time
This line plot tracks Price (All) from the earliest date in the record to the most recent.

Insight: This visualization highlights the historical growth and fluctuations in the UK housing market, providing a clear view of market volatility over time.

3. Feature Correlation (Heatmap)
We calculated the correlation matrix to understand how different price categories (New, Modern, Older) move in relation to one another.

Insight: A high correlation coefficient (approaching 1.0) between these categories indicates that when prices rise in one segment (e.g., 'Modern'), they tend to rise across all market segments.

4. Price Segment Comparison (Boxplot)
This comparison uses a boxplot to view the price distribution across four distinct property types: All, New, Modern, and Older.

Insight: This view helps identify which market segment typically commands higher prices and displays the variance (spread) of prices within each specific category.

##  Conclusion
This analysis successfully transforms raw, time-series housing data into a clear visual narrative. The findings confirm that while individual property segments have distinct price distributions, they are strongly correlated, reflecting broader macroeconomic trends in the UK housing market.
