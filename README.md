# 📊 BCG Financial Data Analysis Project

This project involves the manual extraction and programmatic analysis of financial data from the 10-K filings of **Microsoft**, **Apple**, and **Tesla** over the last three fiscal years. The analysis was conducted using Python and pandas in a Jupyter Notebook environment.

---

## 🧠 Project Objective

To analyze year-over-year financial trends across major tech companies and extract insights that could support the development of an **AI-powered financial chatbot**.

---

## 📁 Files Included

- `bcg_analysis.ipynb` – Jupyter Notebook with all the code, analysis, and markdown commentary.
- `financials.csv` – CSV file containing manually extracted financial data.
- `README.md` – This documentation file.

---

## 📌 Data Source

All data was **manually extracted** from the official 10-K filings available on the **SEC EDGAR database**.

Key financial metrics collected:
- Total Revenue
- Net Income
- Total Assets
- Total Liabilities
- Cash Flow from Operating Activities

---

## 🛠️ Tools & Technologies

- Python 🐍
- Pandas
- Jupyter Notebook
- GitHub
- Excel (for initial data compilation)

---

## 📈 Analysis Overview

The analysis calculates:
- Year-over-Year growth rates for Revenue, Net Income, Assets, Liabilities, and Operating Cash Flow
- Comparisons between companies over time
- Financial trends and stability indicators

Sample code used:
```python
df['Revenue Growth (%)'] = df.groupby('Company')['Total Revenue'].pct_change() * 100
df['
