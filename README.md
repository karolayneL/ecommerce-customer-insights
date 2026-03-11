# 🛒 E-Commerce Data Pipeline & Customer Behavior Analysis

> **From synthetic data generation to actionable customer insights** — a complete data engineering and analytics pipeline for e-commerce.

[![Python](https://img.shields.io/badge/python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![SQLite](https://img.shields.io/badge/sqlite-3-%23003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)
[![Pandas](https://img.shields.io/badge/pandas-1.3%2B-%23150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-%2311545a?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-%23F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Faker](https://img.shields.io/badge/Faker-13.3%2B-%23FF6F61?style=for-the-badge&logo=python&logoColor=white)](https://faker.readthedocs.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 📌 Overview

This project simulates a real-world e-commerce data ecosystem, demonstrating end-to-end capabilities in data engineering and statistical analysis. Using Python's `Faker` library, we generated **2 years of transactional data** across thousands of customers, then modeled it in a normalized SQL database to uncover meaningful patterns in consumer behavior.

Whether you're exploring customer segmentation, seasonal trends, or lifetime value metrics — this pipeline provides a robust foundation.

---

## 🏗️ Data Architecture

The SQLite database follows industry best practices with a clean, normalized schema:

![Database Schema](https://via.placeholder.com/800x400?text=Schema+Diagram+Placeholder)

- **`customers`** — Demographic profiles (age, location, registration date)
- **`categories`** — Product taxonomy and hierarchy
- **`products`** — Items linked to categories with pricing
- **`orders`** — Transaction records with customer and product foreign keys
- **`order_items`** — Line-item details for granular analysis

> *This structure enables sophisticated analytics like cohort analysis, customer lifetime value (LTV), and product affinity studies.*

---

## 🔍 Key Insights & Visualizations

Using Python (Pandas/Matplotlib) for analysis, we uncovered several compelling patterns:

### 1. 💰 Average Ticket by Age Group
**Insight**: Middle-aged customers (35–50) generate the highest average order value — a key segment for targeted marketing.

### 2. 🌍 Geographic Sales Distribution
**Insight**: Sales concentrate in major metropolitan areas, but several mid-sized cities show surprising growth potential.

### 3. 📊 Purchase Frequency Distribution
**Insight**: A small but valuable cohort of "power users" purchases monthly, while most customers shop quarterly — suggesting opportunities for retention campaigns.

<div align="center">
  <img width="1189" height="590" alt="Average Ticket by Age" src="https://github.com/user-attachments/assets/e3f5a9a1-b5e2-472c-b523-bd769fb91acf" />
  <p><em>Figure 1: Average order value across age demographics</em></p>
  
  <img width="990" height="590" alt="Geographic Heatmap" src="https://github.com/user-attachments/assets/7e182922-2449-410f-b4f9-1d47974e8967" />
  <p><em>Figure 2: Sales concentration by city</em></p>
  
  <img width="1389" height="690" alt="Purchase Frequency" src="https://github.com/user-attachments/assets/827f1a6e-2ef2-49d8-b027-ed8e0e70ff48" />
  <p><em>Figure 3: Customer purchase recurrence histogram</em></p>
</div>

---

## 🛠️ Technology Stack

<div align="center">

| **Core Engine** | **Database** | **Data Processing** | **Visualization** | **Development** |
|:---------------:|:------------:|:-------------------:|:------------------:|:---------------:|
| [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org) | [![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org) | [![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/) | [![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/) | [![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/) |
| | | | | [![Faker](https://img.shields.io/badge/Faker-FF6F61?style=for-the-badge&logo=python&logoColor=white)](https://faker.readthedocs.io/) |

</div>

### 🔧 Key Capabilities

- **Data Generation**: 10,000+ synthetic customers with 2 years of purchase history using Faker
- **Database Design**: Fully normalized SQLite schema with foreign key constraints
- **Analysis**: Customer segmentation, cohort analysis, and statistical modeling
- **Visualization**: Publication-ready plots with Matplotlib

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ecommerce-data-pipeline.git
   cd ecommerce-data-pipeline
   ```

2. **Install dependencies**
   ```bash
   pip install faker pandas matplotlib
   ```

3. **Run the pipeline**
   ```bash
   jupyter notebook ecommerce_analysis.ipynb
   ```

4. **Explore the database**
   - The script generates `ecommerce_analytics.db` — connect with any SQLite client
   - Sample SQL queries are included in the `/queries` directory

---

## 📈 Extending the Project

Feel free to fork and build upon this foundation:
- Add **customer lifetime value (LTV)** modeling
- Implement **RFM segmentation**
- Connect to **visualization tools** like Tableau or Power BI
- Deploy as a **real-time dashboard** with Streamlit

---

## 📄 License

This project is open-source under the MIT License — use it for learning, portfolio, or commercial projects.

---

## 🤝 Connect

**Questions? Ideas?** Feel free to open an issue or reach out via [LinkedIn](https://linkedin.com/in/karolayne-lira-1b5501230/) — I'd love to hear how you're using or improving this pipeline.

---

<div align="center">
  <sub>Built with curiosity and a passion for turning raw data into strategic insights.</sub>
  <br>
  <sub>⭐ Star this repo if you find it useful!</sub>
</div>
