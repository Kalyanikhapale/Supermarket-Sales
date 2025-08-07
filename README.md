
# 🛒 Supermarket Sales Analysis

## 📊 Project Overview

In the competitive retail industry, understanding customer behavior, sales trends, and product performance is crucial for maximizing profitability and improving customer satisfaction. This project analyzes supermarket sales data to uncover actionable insights for strategic decision-making.

---

## 🗂️ Project Structure

### 1. 📌 Problem Statement

Define the problem and objectives of the analysis:

* Understand customer behavior
* Identify sales trends
* Evaluate product performance

### 2. 🧼 Data Importing and Cleaning

* **Libraries Import**: `pandas`, `numpy`, `seaborn`, `matplotlib`
* **Data Loading**: Load the `supermarket_sales.csv` dataset
* **Initial Inspection**: Check dataset structure and preview data
* **Data Cleaning**:

  * Handle missing values
  * Drop irrelevant columns (e.g., gross margin percentage with only one unique value)

### 3. 📊 Exploratory Data Analysis (EDA)

* **Customer Demographics**: Gender distribution and visualization
* **Sales Analysis**:

  * Total & average sales
  * Trends over time
  * Peak sales periods
* **Product Performance**:

  * Popular product categories
  * Sales comparison across categories

### 4. 📈 Data Visualization

* **Gender-wise Analysis**: Bar plots, pie charts for purchase patterns
* **Category-wise Analysis**:

  * Sales distribution by category
  * Gender-category correlation
* **Sales Trends**: Line plots for seasonal and peak patterns

### 5. 🔄 Data Transformation

* **Dummy Variables**: Encode categorical columns like `Gender`
* **Merge Data**: Merge transformed data for further analysis

### 6. 💡 Insights and Conclusion

* **Summary of Findings**
* **Strategic Recommendations** based on insights

---

## 🔍 Key Insights

### 1. 👥 Customer Demographics

* Nearly equal gender split: **501 females** and **499 males**
* Indicates balanced marketing reach with a slight female majority

### 2. 🛒 Purchase Patterns

* **Gender-specific Trends**:

  * Females purchase more fashion accessories
  * Males purchase more health & beauty products
* **Sales Volume**:

  * Fashion accessories & health/beauty lead in revenue
  * Seasonal peaks present — helpful for planning

### 3. 📦 Product Performance

* **Top Categories**:

  * Fashion Accessories
  * Health & Beauty
* **Customer Preferences**:

  * Tailored marketing strategies required per gender group

### 4. 🎯 Strategic Recommendations

* **Targeted Marketing**:

  * Fashion for females, health/beauty for males
* **Inventory Management**:

  * Keep top products well-stocked
  * Adjust for seasonal demand
* **Customer Engagement**:

  * Loyalty programs
  * Personalized offers

---

## 🛠️ Getting Started

### 📦 Prerequisites

Make sure the following libraries are installed:

```bash
pip install pandas numpy seaborn matplotlib
```

### ▶️ Running the Notebook

1. Clone the repository or download the `.ipynb` notebook
2. Open it in Jupyter Notebook or JupyterLab
3. Run the cells in order to replicate the analysis

---

## 📁 Repository Structure

```
📦 supermarket-sales-analysis/
│
├── supermarket_sales.csv               # Dataset file
├── Supermarket_sales_analysis.ipynb    # Jupyter notebook with full analysis
└── README.md                           # Project documentation
```

---

## 👤 Author

**Kalyani Khapale**


