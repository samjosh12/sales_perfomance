Sales Performance Analysis using Superstore Dataset:
This project analyzes sales, profit, and discount trends using the Sample Superstore dataset. 
It applies data cleaning, feature engineering, and visualization techniques to uncover insights into business performance across regions, categories, and time.

Dataset:

->The dataset includes orders from a fictional superstore with the following columns:

->Customer information

->Product details

->Sales, profit, discount

->Order and ship dates

->Geography (state, city, region)

->File used: Sample - Superstore.csv (Kaggle/Excel sample dataset)

Objectives:

->Analyze overall and regional sales performance

->Identify profitable and loss-making categories

->Evaluate the effect of discounts on profitability

->Track monthly sales trends

->Prepare cleaned dataset for further modeling or dashboarding

Key Workflow

Data Preprocessing:

->Converted Order Date and Ship Date to datetime format

->Removed duplicates

->Extracted Order Month and Order Year

->Engineered a new metric: Profit Margin = Profit / Sales

Visualizations:

->Bar chart of total sales by region

->Bar chart of profit by product category

->Scatter plot of discount vs profit, colored by category

->Line chart of monthly sales trends over time

Output:

->Saved cleaned dataset as cleaned_superstore_data.csv

Tools Used

->pandas and numpy – data manipulation

->matplotlib and seaborn – visualizations

->Google Colab (notebook-based execution)

Insights Discovered:

->Certain categories generate more profit despite fewer sales

->Discounting has mixed impact on profitability depending on category

->Sales performance varies significantly by region

->Clear monthly trends help in demand forecasting and inventory planning
