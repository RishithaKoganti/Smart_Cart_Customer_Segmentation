# 🛒 Smart Cart Customer Segmentation

An Unsupervised Machine Learning project that leverages K-Means Clustering to discover hidden customer segments based on purchasing behavior, spending habits, demographics, and marketing engagement.

The project helps businesses understand customer groups, improve targeted marketing campaigns, optimize product recommendations, and enhance customer retention strategies through data-driven insights.

---

## 📌 Project Overview

Customer segmentation is a critical business strategy that enables organizations to understand customer behavior and deliver personalized experiences.

Smart Cart Customer Segmentation uses Unsupervised Machine Learning techniques to automatically identify customer groups without predefined labels. By analyzing customer demographics, purchasing behavior, spending patterns, and campaign engagement, the project uncovers meaningful customer segments that can be used for targeted marketing and business decision-making.

---

## 🎯 Objectives

- Identify hidden customer groups using clustering techniques.
- Analyze customer purchasing behavior and spending patterns.
- Understand demographic and lifestyle differences among customers.
- Improve targeted marketing and customer engagement.
- Generate actionable business insights for customer retention.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Customer Behavior Analysis
- K-Means Clustering
- Cluster Profiling
- Customer Segmentation Visualization
- Business Insight Generation

---

## 📊 Dataset Features

### Demographic Features

- Income
- Age
- Education Level
- Marital Status
- Number of Children

### Purchasing Behavior Features

- Total Spending
- NumDealsPurchases
- NumWebPurchases
- NumCatalogPurchases
- NumStorePurchases
- NumWebVisitsMonth

### Customer Information

- Customer Tenure
- Complaint History
- Campaign Response
- Recency

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🤖 Unsupervised Learning Approach

This project uses **Unsupervised Machine Learning**, where no target labels are provided.

### Algorithm Used

### K-Means Clustering

K-Means clustering groups customers based on similarity in their characteristics and purchasing behavior.

Unlike classification problems, customer categories are not known beforehand. The algorithm automatically identifies hidden patterns and segments customers into meaningful groups.

### Number of Clusters

- K = 4

---

## 🔧 Data Preprocessing

The following preprocessing steps were applied:

- Missing Value Handling
- Feature Engineering
- Categorical Encoding
- Feature Scaling using StandardScaler
- Outlier Treatment
- Feature Selection

---

## 📈 Exploratory Data Analysis

EDA was performed to understand:

- Income Distribution
- Spending Behavior
- Purchase Frequency
- Customer Age Distribution
- Campaign Response Trends
- Correlation Between Features
- Customer Demographic Patterns

---

## 📊 Cluster Summary

### Cluster 0 – Moderate Income Family Customers

- Average Income: 39,680
- Average Spending: 222
- Mostly living with partners
- Higher number of children
- Lower campaign response rate

### Cluster 1 – High Value Family Customers

- Average Income: 72,808
- Average Spending: 1,237
- Highest catalog and store purchases
- Strong purchasing power
- Good marketing engagement

### Cluster 2 – Budget Independent Customers

- Average Income: 36,960
- Average Spending: 166
- Mostly living alone
- Lower purchasing activity
- Cost-conscious customers

### Cluster 3 – Premium Independent Customers

- Average Income: 70,723
- Average Spending: 1,190
- Mostly living alone
- Highest campaign response rate
- Excellent target audience for premium marketing campaigns

---

## 📈 Key Insights

### High Value Customers

Clusters 1 and 3 represent the most profitable customer groups.

Characteristics:

- High Income
- High Spending
- Frequent Online Purchases
- Frequent Store Purchases
- Strong Marketing Engagement

### Low Value Customers

Clusters 0 and 2 represent low-spending customer groups.

Characteristics:

- Lower Income
- Lower Purchase Frequency
- Reduced Campaign Engagement
- Higher Price Sensitivity

---

## 📷 Customer Segmentation Visualization

The scatter plot below visualizes customer segments based on:

- Total Spending
- Income

The visualization clearly demonstrates how K-Means successfully separates customers into distinct groups according to purchasing power and spending behavior.

---

## 💡 Business Applications

- Personalized Marketing Campaigns
- Customer Retention Strategies
- Product Recommendation Systems
- Customer Lifetime Value Analysis
- Revenue Optimization
- Customer Relationship Management
- Targeted Promotions

---

## 🔄 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Scaling
6. K-Means Clustering
7. Cluster Evaluation
8. Customer Profiling
9. Business Insight Generation

---

## 📂 Project Structure

```text
Smart_Cart_Customer_Segmentation/
│
├── Smart_Cart_Customer_Segmentation.ipynb
├── marketing_campaign.csv
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Smart_Cart_Customer_Segmentation.git
```

Move to the project directory:

```bash
cd Smart_Cart_Customer_Segmentation
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🔮 Future Enhancements

- Hierarchical Clustering
- DBSCAN Clustering
- PCA-based Visualization
- Customer Lifetime Value Prediction
- Interactive Streamlit Dashboard
- Real-Time Customer Segmentation System

---

## 👨‍💻 Author

**Koganti Rishitha**

Computer Science Student | Machine Learning Enthusiast | Full Stack Developer

### Skills

- Python
- Machine Learning
- Data Analysis
- Data Visualization
- Scikit-Learn
- Pandas
- NumPy

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Your support motivates future Machine Learning and Data Science projects.
