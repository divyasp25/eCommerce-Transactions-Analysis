# eCommerce Transactions Analysis

## Overview

This repository contains the deliverables and code for a comprehensive data science project involving exploratory data analysis, predictive modeling, and clustering on an eCommerce transactions dataset.

The dataset includes three files:
1. **Customers.csv** - Customer profile data.
2. **Products.csv** - Product details.
3. **Transactions.csv** - Transaction history data.

The project is divided into three main tasks:
- **Task 1:** Exploratory Data Analysis (EDA) and Business Insights.
- **Task 2:** Lookalike Model for customer similarity recommendations.
- **Task 3:** Customer Segmentation using clustering techniques.

---

## Table of Contents
- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Assignment Tasks](#assignment-tasks)
- [Deliverables](#deliverables)
- [How to Use](#how-to-use)
- [Results](#results)

---

## Dataset Description

### 1. Customers.csv
- `CustomerID`: Unique customer identifier.
- `CustomerName`: Name of the customer.
- `Region`: Continent of residence.
- `SignupDate`: Registration date.

### 2. Products.csv
- `ProductID`: Unique product identifier.
- `ProductName`: Name of the product.
- `Category`: Product category.
- `Price`: Product price in USD.

### 3. Transactions.csv
- `TransactionID`: Unique transaction identifier.
- `CustomerID`: Linked customer ID.
- `ProductID`: Linked product ID.
- `TransactionDate`: Transaction date.
- `Quantity`: Quantity purchased.
- `TotalValue`: Total transaction value.

---

## Assignment Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Conducted exploratory data analysis to uncover trends and anomalies in the data.
- Derived actionable insights for business strategies.

### Task 2: Lookalike Model
- Developed a customer similarity model based on profile and transaction history.
- Generated a `Lookalike.csv` file with top 3 similar customers for the first 20 customer IDs.

### Task 3: Customer Segmentation
- Applied clustering algorithms for customer segmentation.
- Evaluated clustering quality using metrics like the Davies-Bouldin Index (DB Index).
- Visualized clustering results for business interpretation.

---

## Deliverables

The repository contains the following files:

### Code Files
- **EDA**: `Divyasri_P_EDA.ipynb`
- **Lookalike Model**: `Divyasri_P_Lookalike.ipynb`
- **Clustering**: `Divyasri_P_Clustering.ipynb`

### Output Files
- **EDA Report**: `Divyasri_P_EDA.pdf`
- **Lookalike Recommendations**: `Divyasri_P_Lookalike.csv`
- **Clustering Report**: `Divyasri_P_Clustering.pdf`

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/divyasp25/eCommerce-Transactions-Analysis.git
   cd eCommerce-Transactions-analysis
   ```

2. Open the Jupyter notebooks to explore code for each task:
   - **EDA**: Analyze trends and derive insights.
   - **Lookalike Model**: Run the similarity model.
   - **Clustering**: Segment customers and visualize results.

3. Access the deliverable files for detailed reports and outputs.

---

## Results

### Key Insights from EDA
- Top regions with the highest number of transactions.
- Product categories driving revenue growth.
- Seasonal trends in customer purchasing patterns.

### Lookalike Model
- Customers with similar profiles and transaction behavior identified with similarity scores.

### Clustering
- Successfully segmented customers into clusters, optimizing business targeting strategies.
