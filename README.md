# Task 2: Customer Segmentation using Unsupervised Learning 
* **Objective**
​The goal is to group customers based on their purchasing behavior and demographics using unsupervised learning techniques. This helps businesses understand different customer personas and create targeted marketing strategies.
​* **Approach**
​Data Preprocessing: Cleaned the dataset (like Mall Customers or E-commerce data) and handled outliers.
​Feature Selection: Focused on features like Annual Income, Spending Score, or RFM (Recency, Frequency, Monetary) metrics.
​Clustering Algorithm: Implemented the K-Means Clustering algorithm.
​Optimal Clusters: Used the Elbow Method to find the ideal number of clusters (k).
​Visualization: Plotted the clusters in 2D or 3D to visualize distinct customer groups.
​* **Results and Findings**
​Customers were successfully segmented into groups such as "High Spenders," "Budget Conscious," and "Target Customers."
​It was found that a specific group (e.g., high income but low spending) represents a significant opportunity for re-engagement campaigns.

# Task 3: Household Energy Consumption Forecasting
​* **Objective**
​To analyze and forecast household electrical energy consumption using historical time-series data to assist in energy planning and efficiency.
​* **Approach**
​Time-Series Analysis: Resampled minute-wise data into daily averages to identify trends and seasonality.
​Modeling: Compared three different models: ARIMA, XGBoost (with lag features), and Prophet.
​Evaluation: Measured performance using MAE and RMSE metrics.
​* **Results and Findings**
​XGBoost and Prophet captured the daily fluctuations more accurately than the baseline ARIMA model.
​The analysis highlighted specific peak hours and days, providing insights for energy optimization.

# Task 5: Interactive Business Dashboard (Streamlit)
​* **Objective**
​To develop an interactive web-based dashboard for visualizing business performance metrics using the Global Superstore dataset.
​* **Approach**
​Data Preparation: Cleaned the Global Superstore dataset and ensured sales/profit data was in numeric format.
​Web App Development: Built a Streamlit application with interactive sidebar filters for Region, Category, and Sub-Category.
​KPI Design: Integrated charts to display Total Sales, Profit, and Top 5 Customers.
​* **Results and Findings**
​The dashboard enables users to identify which product categories are driving the most profit across different regions instantly.
​Stakeholders can now perform self-service data analysis without needing complex SQL queries.
