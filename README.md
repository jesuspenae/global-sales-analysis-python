# 📊 Global Sales Analysis (2010–2017)

An end‑to‑end data analysis project focused on understanding global sales 
performance across product categories, regions, sales channels, and time 
periods. Includes data cleaning, feature engineering, exploratory analysis, 
visualizations, and business insights.

---

## ✅ Overview  
This project uses a real-world–structured dataset with three tables:

| File | Description |
|------|-------------|
| `events.csv` | Sales transactions |
| `products.csv` | Product catalog |
| `countries.csv` | Countries and regions |

The goal is to combine, clean, and analyze these datasets to uncover business 
insights related to revenue, profit, shipping times, product mix, and more.

---

## 🧹 **1. Data Cleaning**
Key steps performed:

- Removed inconsistent or incomplete records  
- Converted date columns to `datetime`  
- Filled missing country codes (`Unknown`)  
- Standardized product and country information  
- Created financial columns (Revenue, Cost, Profit)  
- Verified duplicates and anomalies  
- Added temporal features (Year, Day of Week, Shipping Days)

---

## 📈 **2. Business KPIs**
| Metric | Value |
|--------|--------|
| Total Orders | **1,328** |
| Total Revenue | **1.702M USD** |
| Total Profit | **501M USD** |
| Profit Margin | **34.1%** |
| Countries Covered | **45** |
| Period Analyzed | **2010–2017** |

---

## 🔍 **3. Key Insights**

### 🛍️ Products
- **Cosmetics**: Highest absolute profit (92.7M USD).  
- **Clothes**: Highest margin (67.2%), lower volume.  
- **Meat**: Lowest margin (13.6%).  
- **Fruits**: Minimal presence.

### 🌍 Geography
- **Europe = 89%** of global profit → main market.  
- Small European countries (Andorra, Malta, San Marino) are unusually strong performers.  
- Asia contributes modestly (26.9% margin).

### 🛒 Sales Channels
- Online vs Offline → *nearly identical* profit and volume.  
- The channel is **not** a profitability driver.

### 🚚 Shipping
- Average shipping time: **24.8 days**.  
- **No correlation** between shipping delay and profit.  
- Fastest category: *Personal Care*.

### 📅 Time Trends
- Peak year: **2012** (285M revenue, 87M profit).  
- Downward trend since 2013.  
- 2017 data is partial.

### 📆 Days of Week
- Orders evenly distributed.  
- Fridays yield slightly higher per‑order profit.  
- No weekly seasonality by product.

---

## 📘 Notebook  
📄 Full analysis is available in:  
➡️ `notebook/Global_Sales_Analysis.ipynb`

---

## 🛠️ **Tech Stack**
- Python  
- Pandas / NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📁 Repository Structure
