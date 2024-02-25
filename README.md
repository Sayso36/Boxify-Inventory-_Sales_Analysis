Project Title - ANALYSIS OF BOXIFY INVENTORY AND SALES (1900 - 2018)

Overview - The project focus on analyzing a dataset containing information about product sales and inventory levels. The dataset includes details such as SKU numbers, sold counts, item counts, release years, etc. The objective is to gain insights into inventory management, identifying top-selling products, understanding sales trends, and deriving key performance indicators (KPIs) related to inventory turnover, stock-to-sales ratio, and reorder points of the year from 1900 to 2018. The main focus of the project is to analyze sales over trend and inventory performance for better business management efficiency.

Objectives - Inventory Analysis: Understand the inventory dynamics, including turnover rates, stock levels, and low-stock items.
Top Selling Products Identification: Identify the top-selling products based on the sum of sold counts.
Inventory KPI Calculation: Compute key inventory KPIs such as inventory turnover, stock-to-sales ratio, and reorder point.
Sales Trend Analysis: Visualize and interpret sales trends over time to identify patterns and anomalies.
Inventory Metrics Visualization: Visualize inventory metrics to gain insights into inventory management performance.

Methodology - Data Handling: The project starts with importing necessary libraries and loading the dataset using pandas. Basic exploratory data analysis (EDA) functions like .info() and .describe() are used to understand the dataset's structure and summary statistics.Data Preprocessing: Missing data is handled using forward fill method (method = "ffill") to propagate non-null values forward. This ensures continuity in the data without introducing significant bias.Top Selling Products: Grouping by SKU number and summing the sold counts helps identify the top 15 selling products.Low Stock Items Identification: Items with counts less than 10 are classified as low-stock items. This helps in understanding inventory levels that may need attention or replenishment.Inventory KPI Calculation: Key inventory performance indicators like inventory turnover, stock-to-sales ratio, and reorder point are calculated. These metrics provide insights into inventory management efficiency and help in optimizing stock levels.Sales Trend Analysis: Sales trends over time are visualized using a line plot, allowing for the identification of trends and anomalies.Inventory Metrics Visualization: Inventory metrics such as turnover, stock-to-sales ratio, and reorder point are visualized using bar plots. This provides a clear overview of inventory management performance and highlights areas for improvement.

Conclusion - In conclusion, by embracing a data-driven approach to inventory management, businesses can streamline operations, improve efficiency, and ultimately achieve sustainable growth and success in the competitive marketplace.





