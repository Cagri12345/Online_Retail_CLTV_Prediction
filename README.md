# 🛍️ Online Retail CLTV Prediction

This project aims to predict the Customer Lifetime Value (CLTV) of an online retail company based in the UK using real transactional data. The objective is to help the company make data-driven decisions regarding marketing strategies and resource allocation.

## 🔍 Project Objective

With accurate CLTV predictions, companies can:

- Segment their customers effectively,
- Focus marketing efforts on high-value customers,
- Optimize customer retention strategies.

## 📊 Dataset Information

- **Source:** UCI Machine Learning Repository – Online Retail II  
- **Date Range:** 01/12/2009 - 09/12/2011  
- **Description:** This dataset includes online transactions for a UK-based retail company that sells mostly gift items. The majority of customers are wholesalers.

## 🔧 Techniques Used

- Data Cleaning & Preprocessing  
- RFM Analysis (Recency, Frequency, Monetary)  
- BG/NBD Model – Predicts customer purchase frequency  
- Gamma-Gamma Model – Estimates average transaction value  
- CLTV Calculation  
- Customer Segmentation

## 📚 Libraries Used

- pandas  
- matplotlib  
- datetime  
- lifetimes  

> The `lifetimes` package is used for CLTV modeling with `BetaGeoFitter` and `GammaGammaFitter`.

## 📁 Project Files

- `Online_Retail_CLTV_Prediction.ipynb`: Jupyter Notebook containing the full pipeline of data processing, modeling, and analysis.

## 🧠 Notes

- Transactions with invoice numbers starting with `"C"` (canceled orders) were removed.  
- Records with missing `CustomerID` were excluded.  
- CLTV was calculated for a **6-month forecast period**.

## ✨ Outputs

- Customers were segmented based on their CLTV scores.  
- These segments can be used to create personalized marketing campaigns and improve return on investment.
