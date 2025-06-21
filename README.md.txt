# 🧠 Customer Segmentation with RFM Analysis and K-Means Clustering

This project segments customers using Recency, Frequency, and Monetary analysis combined with K-Means clustering to uncover valuable business insights.

The goal is to automatically group customers based on their purchasing behavior to support business decisions in marketing, retention, and sales strategy.

---

## 📊 Tools & Technologies

- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Machine Learning**: K-Means Clustering
- **Data Source**: Online Retail dataset (Excel format)
- **Optional Visualization**: Power BI


The dataset is from an online retail store containing transactions between 2010 and 2011. It includes information on invoice numbers, product descriptions, quantities, prices, and customer IDs.

## Methodology

1. Data Cleaning: Removed invalid and missing data.
2. Calculated RFM metrics: Recency, Frequency, Monetary.
3. Normalized data using StandardScaler.
4. Applied K-Means clustering to segment customers.
5. Analyzed and labeled customer segments.
6. Exported results for Power BI dashboard.


After applying RFM analysis combined with K-Means clustering, we identified four distinct customer segments with unique purchasing behaviors and business implications:

1. High-Value Customers
- **Characteristics:**  
  - Low Recency (purchased recently)  
  - High Frequency (buy often)  
  - High Monetary value (spend a lot)  
- **Business Implications:**  
  - These are loyal, profitable customers.  
  - Prioritize them for exclusive offers, loyalty programs, and upselling.  
  - Maintain high engagement to sustain revenue.

2. At-Risk Customers
- **Characteristics:**  
  - High Recency (have not purchased for a long time)  
  - Moderate to low Frequency  
  - Moderate Monetary value  
- **Business Implications:**  
  - Customers who may be drifting away.  
  - Target with win-back campaigns and personalized promotions to reactivate them.  
  - Monitor their behavior to prevent churn.

3. Potential Customers
- **Characteristics:**  
  - Moderate Recency  
  - Moderate Frequency  
  - Moderate Monetary value  
- **Business Implications:**  
  - Customers with growth potential.  
  - Encourage through targeted marketing and cross-selling.  
  - Use segmentation to tailor communication and increase lifetime value.

 4. New Customers
- **Characteristics:**  
  - Very low Frequency (few purchases)  
  - Variable Recency  
  - Low to moderate Monetary value  
- **Business Implications:**  
  - Recent buyers still exploring the product range.  
  - Focus on onboarding, education, and incentives to increase purchase frequency.  
  - Build trust to convert them into loyal customers.

---

Summary Statistics by Segment

| Segment          | Avg Recency (days) | Avg Frequency | Avg Monetary (currency) | # Customers |
|------------------|--------------------|---------------|------------------------|-------------|
| High-Value       | 15                 | 12            | 5000                   | 450         |
| At-Risk          | 120                | 3             | 1200                   | 700         |
| Potential



## 🤝 Contact

📧 cdavid9607@gmail.com
🔗 https://www.linkedin.com/in/cristiangarciagonzalez/
🌍 Available for freelance, remote, or relocation opportunities — especially in data-driven environments like Dubai.

---
