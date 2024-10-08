# Global Superstore Data Analysis and Model Implementation

## Project Overview
This project analyzes the Global Superstore dataset, providing insights into sales, profit margins, shipping times, and customer segmentation. It includes data preprocessing, exploratory data analysis, feature engineering, and predictive modeling. The goal is to derive actionable insights for business decision-making.

## Key Objectives
- Perform data cleaning and handle missing values.
- Analyze key metrics like sales distribution, profit margin, and days to ship.
- Visualize correlations and trends using heatmaps, histograms, and scatter plots.
- Implement machine learning models like KMeans Clustering and Linear Regression to predict profit and segment customers.
- Conduct feature importance analysis using Random Forest.
- Explore hyperparameter tuning using GridSearchCV for model optimization.

## Table of Contents
1. Data Loading and Preview
2. Data Quality Check
3. Descriptive Statistics
4. Correlation Analysis
5. Sales Distribution Analysis
6. Sales by Category
7. Feature Engineering
8. Monthly Sales Trend Analysis
9. KMeans Clustering
10. Linear Regression for Profit Prediction
11. Model Evaluation
12. Feature Importance with Random Forest
13. Hyperparameter Tuning with GridSearchCV
14. Regional Sales Analysis
15. Sales vs Profit Scatterplot
16. Cluster-Based Insights for Marketing

## Dataset Description
The dataset includes sales transactions from the Global Superstore, covering categories such as Furniture, Office Supplies, and Technology. The dataset contains the following fields:
- Order Date
- Ship Date
- Sales
- Profit
- Quantity
- Discount
- Category
- Region
- Customer ID
- Product ID

## Key Insights and Visualizations
- **Sales Distribution**: A histogram showing the distribution of sales values.
- **Correlation Heatmap**: Identifies correlations between key numerical variables like Sales, Profit, and Quantity.
- **Sales by Category**: A boxplot visualizing the variation of sales across product categories.
- **Monthly Sales Trend**: A line plot analyzing sales trends over time.
- **KMeans Clustering**: Visualizing customer segments based on sales behavior.
- **Regression Analysis**: Predicting profit based on sales, discount, and quantity.

## Machine Learning Models
- **KMeans Clustering**: Segments customers into three clusters based on numerical attributes.
- **Linear Regression**: Predicts profit using sales, discount, and quantity as input features.
- **Random Forest Regressor**: Determines feature importance and provides more accurate profit predictions.
- **Grid Search**: Optimizes hyperparameters for the Random Forest model to improve performance.

## Conclusion
This project provided an in-depth analysis of sales, profit, and customer segmentation for the Global Superstore dataset. The combination of data exploration, feature engineering, and predictive modeling offers valuable insights for optimizing business strategies, from targeted marketing to operational efficiency improvements.

## Future Work
- Further model tuning and exploration of other algorithms like Decision Trees or Gradient Boosting.
- Creating dynamic dashboards with Power BI for deeper data exploration.
- Exploring more granular customer segmentation to enhance targeted marketing efforts.

## Instructions to Run the Code
- Install required libraries: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.
- Load the dataset and execute the Jupyter Notebook cells step-by-step.

## Repository Structure
- `Global_Superstore_EDA.ipynb`: Jupyter Notebook containing the analysis and code.
- `Global_Superstore_Data.csv`: Dataset file (if stored locally or via a link).
