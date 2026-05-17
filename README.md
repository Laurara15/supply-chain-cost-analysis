# 📦 Supply Chain Cost Analysis & Efficiency

> End-to-end data analysis project exploring cost efficiency, anomaly detection, and actionable recommendations across a supply chain dataset.

-----

## 📌 Overview

This project analyzes supply chain operational data to uncover hidden cost inefficiencies, detect anomalies, and deliver data-driven recommendations for business optimization.

**Key Questions Answered:**

- Which suppliers deliver the best cost-to-revenue ratio?
- Which transportation mode is most cost-efficient?
- Are there abnormal cost spikes that need attention?
- How does defect rate impact manufacturing cost?

-----

## 🗂️ Project Structure

```
supply-chain-cost-analysis/
│
├── supply_chain_cost_analysis.ipynb   # Main analysis notebook
├── supply_chain_data.csv              # Dataset (source: Kaggle)
├── images/
│   ├── product_distribution.png
│   ├── cost_distribution.png
│   ├── correlation_heatmap.png
│   ├── supplier_cost_analysis.png
│   ├── transport_analysis.png
│   ├── anomaly_detection.png
│   └── defect_cost_scatter.png
└── README.md
```

-----

## 🔍 Analysis Highlights

### 1. Exploratory Data Analysis (EDA)

- Distribution of product types and revenue contribution per category
- Cost distribution for shipping, manufacturing, and total costs
- Correlation heatmap across key numerical variables

### 2. Cost Efficiency Analysis

- **Supplier comparison**: Average manufacturing & shipping cost per supplier, ranked by cost efficiency ratio (Revenue / Total Cost)
- **Transportation modes**: Cost and delivery time trade-offs across air, sea, road, and rail
- **Location analysis**: Average operational costs and defect rates per city

### 3. Anomaly Detection

- IQR-based anomaly detection on shipping, manufacturing, and total costs
- Visual boxplot inspection for outlier identification
- Defect rate vs. manufacturing cost scatter analysis

-----

## 💡 Key Insights

- Suppliers with the **highest cost efficiency ratio** generate significantly more revenue per dollar spent — renegotiating contracts with low-efficiency suppliers could improve margins
- **Road and sea transport** tend to offer lower average shipping costs vs. air, suitable for non-urgent shipments
- Products in the **top 25% defect rate quartile** show higher average manufacturing costs, suggesting quality issues drive cost overruns
- Several SKUs were flagged as **cost anomalies** — these warrant further investigation to rule out data errors or process inefficiencies

-----

## 🛠️ Tools & Libraries

|Tool      |Purpose                        |
|----------|-------------------------------|
|Python 3.x|Core programming language      |
|Pandas    |Data manipulation & aggregation|
|NumPy     |Numerical computation          |
|Matplotlib|Data visualization             |
|Seaborn   |Statistical visualizations     |
|SciPy     |Z-score outlier detection      |

-----

## 📊 Dataset

**Source:** [Supply Chain Dataset — Kaggle](https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis)

The dataset includes product-level supply chain information covering:

- Product type, SKU, price, revenue
- Supplier name and location
- Shipping costs, times, and transportation modes
- Manufacturing costs and defect rates
- Stock levels and order quantities

-----

## ▶️ How to Run

1. Clone this repository
   
   ```bash
   git clone https://github.com/Laurara15/supply-chain-cost-analysis
   cd supply-chain-cost-analysis
   ```
1. Install dependencies
   
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
1. Place `supply_chain_data.csv` in the project root directory
1. Open and run the notebook
   
   ```bash
   jupyter notebook supply_chain_cost_analysis.ipynb
   ```

-----

## 📈 Business Recommendations

1. **Optimize Supplier Mix** — Prioritize suppliers with high cost efficiency ratios; re-evaluate contracts with underperforming ones
1. **Mode Shift for Non-Urgent Shipments** — Shifting eligible shipments to lower-cost transport modes can reduce shipping spend
1. **Quality Control Investment** — Reducing defect rates in high-defect SKUs directly lowers manufacturing costs
1. **Real-Time Cost Monitoring** — Implement anomaly detection dashboards to catch cost spikes before they escalate

-----

## 👩‍💻 Author

**Laura Rizka Amanda**  
Data Analyst | Python · SQL · Data Visualization

[![GitHub](https://github.com/Laurara15)

-----

*This project is part of my data analytics portfolio.*