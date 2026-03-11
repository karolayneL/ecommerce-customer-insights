# E-Commerce Data Pipeline & Customer Behavior Analysis 🛒

This repository presents a complete data ecosystem for a fictional e-commerce platform, focused on data engineering (generation and modeling) and statistical analysis of consumer behavior.

## 📊 The Project
The goal is to simulate a real-world environment where data from thousands of customers and millions of transactions needs to be structured for analysis. The project uses the `Faker` library to create a 2-year purchase history, enabling studies on seasonality and customer profiles.

## 🏗️ Data Architecture (SQL)
The SQLite database was modeled following best normalization practices:
- **Customers**: Demographic profile (Age, Location).
- **Categories**: Product segmentation.
- **Orders**: Financial transactions with foreign keys, enabling LTV (Lifetime Value) analysis.

## 💡 Insights Extracted
Through the notebook, we performed:
1.  **Average Ticket Analysis**: Comparison of spending across different age groups.
2.  **Geographic Distribution**: Identification of cities with the highest sales volume.
3.  **Purchase Frequency**: Histogram of customer purchase recurrence.

## 🛠️ Technologies
- **Python**: Core processing engine.
- **SQLite**: Relational database engine.
- **Pandas & Matplotlib**: Data wrangling and visualization.
- **Faker**: Massive synthetic data generation.

## 🚀 How to Use
1.  Install dependencies: `pip install faker pandas matplotlib`
2.  Run the notebook to generate the `ecommerce_analytics.db` database.
3.  Use the included SQL scripts to extract your own reports too!
