# 📊 E-Commerce Sales Analysis and Customer Insights  

This project analyzes the UK E-Commerce dataset (2010–2011) to uncover sales patterns and customer behavior.  

## 📂 Dataset
- Source: Kaggle (UK E-Commerce Dataset)
- Size: ~500,000 transactions
- Features: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country  

## 🛠️ Steps Performed
1. Data Cleaning (handling nulls, duplicates, incorrect entries)  
2. Exploratory Data Analysis (sales trends, revenue patterns, country-wise analysis)  
3. RFM Analysis (Recency, Frequency, Monetary)  
4. Customer Segmentation using K-Means clustering  
5. Business Insights & Recommendations  

## 📈 Key Insights
- Most customers are from the UK (~90% of sales).  
- Seasonal spikes observed during November–December.  
- A small percentage of customers drive majority of revenue (Pareto principle).  
- High-value customers can be targeted for loyalty programs.  

## 🧰 Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- Jupyter/Kaggle Notebook  

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook E-Commerce-Sales-Analysis.ipynb
