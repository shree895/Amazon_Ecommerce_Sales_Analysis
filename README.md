# Amazon E-commerce Sales Analysis

## Project Objective
Analyze Amazon product sales, ratings, and reviews to gain insights into product performance, customer engagement, and category trends.

## Dataset
- File: cleaned_amazonsales_analysis.csv  
- Description: Cleaned dataset containing product information, ratings, reviews, and reviewer details.

## Analysis Performed
1. *Data Cleaning*
   - Renamed columns for clarity
   - Converted numeric columns (rating, rating_count, etc.) to correct types
   - Handled missing values

2. *Exploratory Data Analysis (EDA)*
   - *Ratings Analysis:* Distribution of product ratings and top-rated products
   - *Category Analysis:* Top 10 categories by number of products and average ratings
   - *Reviewer Analysis:* Top 10 most active reviewers
   - *Review Analysis:* Word cloud to visualize common words in customer reviews
   - *Correlation Analysis:* Heatmap showing correlation between ratings and review counts

## Key Insights
- Top-reviewed products indicate high popularity
- Certain categories consistently have higher average ratings
- Most common words in reviews highlight what customers value most
- Top reviewers represent the most engaged users
- Correlation between rating and review count shows patterns of product popularity

## How to Run
1. Open Amazon_Ecommerce_Sales_Analysis.ipynb in Jupyter Notebook or Google Colab
2. Ensure cleaned_amazonsales_analysis.csv is in the same directory
10. Run all cells from top to bottom to reproduce analysis and visualizations

## Optional Enhancements
- Bubble charts for category performance
- Boxplots for rating distribution per category
- Sentiment analysis on reviews
- Interactive dashboard using Streamlit or Plotly Dash
