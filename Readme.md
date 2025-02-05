# 🛒 Customer Insights Dashboard

## 📌 Overview
This project is part of the **Machine Learning Internship at iGnosis Tech**. The goal is to analyze customer purchasing behavior and create a **dashboard using Plotly and Dash** to visualize key insights from the given dataset.

## 🔍 Problem Statement
The task involves analyzing customer transactions and generating data-driven recommendations based on:
- **Customer Spending by Segment**
- **Top-Selling Products**
- **Total Transactions per Customer Segment**

## 📊 Dataset
The dataset consists of **customer transactions**, including fields like:
- `TXN_ID` (Transaction ID)
- `LIFESTAGE` (Customer life stage)
- `PREMIUM_CUSTOMER` (Whether the customer is premium or not)
- `PROD_NAME` (Product purchased)
- `TOT_SALES` (Total sales value of the transaction)

## 🚀 Tech Stack
- **Python** (Data Analysis & Dashboard Development)
- **Pandas** (Data Wrangling)
- **Plotly & Dash** (Data Visualization)
- **Jupyter Notebook** (Development & Execution)

## 📈 Dashboard Features
The dashboard consists of three visualizations:
1. **Customer Spending by Segment** – A grouped bar chart to analyze spending patterns across different customer segments.
2. **Top 3 Best-Selling Products** – A horizontal bar chart showing the highest revenue-generating products.
3. **Total Transactions per Customer Segment** – A grouped bar chart to compare the number of transactions across customer segments.

## 🛠️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ml-internship-ignosis.git
   cd ml-internship-ignosis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the dashboard:
   ```bash
   python app.py
   ```
4. Open your browser and go to: `http://127.0.0.1:8050/`

## 📂 File Structure
```
.
├── data/                 # Raw & Processed Data
├── app.py                # Dash Application
├── requirements.txt      # Python Dependencies
├── README.md             # Project Documentation
└── notebooks/            # Jupyter Notebooks for Analysis
```

## 🎯 Key Takeaways
- Premium customers contribute significantly to total sales.
- Certain product categories have a higher purchase rate.
- Customer segmentation helps in targeted marketing strategies.

## 🔗 References
- [Dash Documentation](https://dash.plotly.com/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Plotly Documentation](https://plotly.com/python/)

---
📧 **Author:** Shrish Kamboj  
🌍 **LinkedIn:** [Your Profile](https://linkedin.com/in/your-profile)  
🚀 **GitHub:** [Your GitHub](https://github.com/your-username)

