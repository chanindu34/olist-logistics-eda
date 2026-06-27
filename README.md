# 📦 Olist Logistics Performance Analysis

> **Business Objective**: Identifying systemic delivery bottlenecks and operational inefficiencies within the Olist e-commerce supply chain to optimize logistics performance.

---

## 📊 Executive Summary
![Executive Dashboard](image_54bd57.png)

## 🚀 Key Insights
* **Logistics Efficiency**: The network demonstrates an average **12-day early delivery** rate, indicating a clear opportunity to tighten delivery timeframes.
* **Operational Risk**: Identified catastrophic outliers with delivery delays extending up to **188 days**.
* **Pricing Strategy**: Analysis shows **no correlation between item price and delivery speed**, suggesting an opportunity for tiered shipping SLAs.
* **Regional Bottlenecks**: Significant variance in delay metrics across states highlights the need for secondary distribution nodes.

---

## 🛠 Technical Implementation

### 1. Data Pipeline
* **Fusing Relational Data**: Performed `INNER JOIN` operations to integrate four primary datasets into a single master logistics pipeline.
* **Data Integrity**: Implemented a cleaning suite to handle missing delivery timelines, ensuring 100% data reliability for 110k+ records.

### 2. Feature Engineering
* Calculated `delivery_delay_days` (Actual vs. Estimated delivery) to establish a baseline for operational performance.

---

## 📈 Tech Stack
* **Language**: Python
* **Data Manipulation**: Pandas, NumPy
* **Visualization**: Seaborn, Matplotlib

## 🚀 How to Run
1. **Clone**: `git clone <your-repo-url>`
2. **Install**: `pip install pandas seaborn matplotlib`
3. **Analyze**: Open `olist_logistics_analysis.ipynb` in VS Code.