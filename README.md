# 🚀 Superstore Sales Performance Dashboard  

Welcome to the *Superstore Sales Performance Dashboard* repository! This project features an interactive *Power BI Dashboard* designed for analyzing and forecasting sales performance using the *Superstore dataset*. Gain insights into sales trends, regional performance, customer segmentation, and product category contributions to optimize decision-making.  

---

## 🌟 Overview  

The dashboard is designed to visualize key sales and profit metrics, analyze regional and categorical performance, and provide a clear understanding of sales trends. It includes the following: 
- 📊 *Key Performance Indicators (KPIs)*: For Total Sales, Profit, Growth Rates, and more.  
- 🌍 *Regional Analysis*: Uncover trends across different regions.  
- 🛒 *Category Insights*: Deep dive into product-level performance.  
- 👥 *Customer Segmentation*: Identify high-value customers.  
- 📈 *Sales Forecasting*: Predict future trends using time series models.  
- 🎛 *Interactive Filters*: Explore data dynamically.  

---

## 📈 Dashboard Insights  

### *1. Key Metrics*  
| Metric              | Value      |  
|---------------------|------------|  
| *Total Sales*     | 2.30M     |  
| *Total Profit*    | 286.4K    |  
| *Profit Margin*   | 12%        |  
| *MoM Growth*      | 18.39%     |  
| *YoY Growth*      | 2.77%      |  

These metrics highlight consistent growth, with room for improving profitability.  

---

### *2. Regional Analysis*  
#### Sales Contribution:  
- 🏅 *West*: 31.58% (Highest Sales).  
- 🥈 *South*: 17.05% (Lowest Sales).  

#### Profit Margins:  
- ✅ *West*: 15% (Highest Profitability).  
- ⚠ *Central*: 8% (Struggling despite significant sales).  

*Insight*: Target marketing campaigns in the West for improved sales while maintaining profitability.  

---

### *3. Product Category Analysis*  
#### Sales by Category:  
| Category          | Sales       |  
|-------------------|-------------|  
| *Technology*    | 836.15K    |  
| *Furniture*     | 742.06K    |  
| *Office Supplies*| 719.05K    |  

*Insight: Technology leads in sales and profit. Boost **Office Supplies* campaigns to balance category growth.  

---

### *4. Customer Segmentation*  
- *High-Spending Customers*: Account for a majority of revenue.  
- *Low-Spending Customers*: Opportunity for targeted promotions.  

*Actionable Insight*: Introduce loyalty programs to retain high-value customers.  

---

### *5. Sales Growth Trends*  
Steady sales growth with seasonal spikes indicates opportunities for:  
- Seasonal promotions.  
- Cross-selling high-demand products.  

---

### *6. Geographical Insights*  
#### Top Performing States:  
- 🥇 *California*: Leading in sales.  
- 🥈 *Texas city* & *New York city*: Strong contributors.  

#### States with Growth Potential:  
- Idaho and Wyoming: Low sales but high growth opportunities.  

---

### *7. Sales Forecasting Using Time Series Models*  
This project includes *sales forecasting* to predict future sales trends using *time series models*.  

#### Key Features:  
- 📅 *Forecast Horizon*: Monthly sales projections for the next 12 months.  
- 🧠 *Models Used*:  
  - ARIMA (Auto-Regressive Integrated Moving Average).  
  - SARIMA (Seasonal ARIMA).  
  - Prophet by Facebook for handling seasonality.  
- 🔍 *Evaluation Metrics*: MAPE, RMSE, and R-squared to assess model performance.  

#### Forecasting Insights:  
- Predicts continued *positive growth trends* for the upcoming quarters.  
- Seasonal variations are captured, enabling better planning during peak months.  
- Helps in resource allocation, inventory management, and sales target setting.  

---

## 🎯 Key Takeaways  

1. *Regional Focus: Prioritize sales strategies in the **West** while improving profitability in underperforming regions like Central.
2. *Category Growth: **Technology** leads in performance. Increase focus on **Office Supplies** to ensure balanced growth across all categories.  
3. *Customer Strategy: Retain **high-spending customer**s by offering **loyalty programs** and **exclusive deals**. 
4. *Sales Forecasting: Leverage forecasts to **align strategies** with projected growth.
---

## 💡 Features  

### Interactive Filters  
- 🚚 *Shipping Modes*: First Class, Same Day, Standard.  
- 🌎 *Regions*: Central, East, South, West.  
- 📅 *Timeframes*: Yearly and Monthly.  
- 🛒 *Product Categories*: Furniture, Office Supplies, Technology.  

### Visualizations  
- 📌 *Pie Charts*: Sales breakdown by region and category.  
- 📈 *Line Charts*: Monthly sales growth and forecast trends.  
- 📍 *Geographical Maps*: Sales by state and city.  
- 📊 *Bar Graphs*: Total Sales, Total Spend, ROI and marketing performance.  

---

## 🛠 How to Use  

### 1. Clone the Repository  
Clone this repository using:  
```bash  
git clone https://github.com/ArpiCodes/superstore-sales-Performance-Dashboard.git  
```  

### 2. Open in Power BI  
1. Install [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).  
2. Open the **Sales Performance Dashboard.pbix** file.  
3. Explore the interactive dashboard using slicers and filters.  

### 3. Access Forecasting Models  
1. Open the **Sales Forecasting Using Time Series Models.ipynb** file in Jupyter Notebook.  
2. Install dependencies using:  
  ```bash
   pip install -r requirements.txt
  ```
3. Run the notebook to explore and visualize forecasts.  

---

## 🚀 Future Enhancements  

1. *Integrate Additional Data*: Include marketing and competitor metrics.  
2. *Enhanced Forecasting Models*: Explore hybrid models like LSTM-ARIMA.  
3. *Real-Time Insights*: Implement dashboards with real-time anomaly detection.  

---


🌟 *Analyze, Forecast, and Optimize with the Superstore Sales Performance Dashboard!*  
