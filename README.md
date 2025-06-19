---

📊 Adidas Sales Dataset Analysis

📝 Overview

This project performs a comprehensive analysis of the Adidas Sales Dataset to understand sales performance across regions, products, and sales methods. Key metrics such as seasonal trends, monthly/yearly performance, product contributions, and operating profit are explored. The objective is to generate actionable insights and business recommendations to help Adidas optimize its sales strategies and profitability.


---

📁 Dataset Description

The dataset includes transactional sales records with the following key fields:

Engineered Features:


---

🎯 Project Objectives

Clean and preprocess Adidas sales data

Analyze sales performance across:

Products

Regions

Retailers

Sales methods

Time (month, season, year)


Calculate product contribution to overall sales

Estimate operating profit

Recommend data-driven strategies



---

🔍 Exploratory Data Analysis (EDA)

🛒 Sales Method Analysis

Retail is the dominant channel, generating over 50% of total revenue.

Online sales showed steady growth, particularly in Q2 and Q3.

Wholesale had fewer transactions but higher average profit margins.


📅 Time-Based Analysis

Monthly Trends:

Peak months: June, August, November

Lowest sales observed in February and September


Yearly Trends:

Year-over-year growth in total revenue and profit.

Profit margins improved marginally each year.


Seasonal Analysis:

Summer (Jun–Aug) showed the highest revenue and units sold.

Winter had strong profit performance due to holiday shopping.

Spring and Fall showed moderate, stable trends.



📦 Product Sales Contribution

Footwear: ~40% of total sales

Apparel: ~35%

Accessories and Equipment: ~25% combined


> 🔹 Footwear not only leads in revenue but also shows strong operating profit margins.



💰 Operating Profit Analysis

Operating Profit = Total Profit - (0.15 × Total Revenue)

Products with high volume and medium pricing had the best profitability.

Average Operating Profit Margin across the dataset: 18–22%



---

📊 Visualizations

Visual insights were created using Python libraries such as matplotlib, seaborn, and plotly:

Sales by Method (Bar Chart)

Monthly Revenue Trends (Line Chart)

Seasonal Revenue Heatmap

Product Sales % (Pie Chart)

Operating Profit by Product (Bar Chart)



---

📈 Key Insights

Retail & Footwear are core to Adidas’ sales success.

Online sales are growing rapidly—especially post-spring.

Summer is the most profitable season across all years.

Certain regions like North America outperform others by a wide margin.

Apparel has slightly lower margins compared to footwear, despite strong sales.



---

✅ Business Recommendations

1. Invest in Online Infrastructure
Enhance digital platforms and campaigns for Q2–Q3 to capitalize on online growth.


2. Focus on Summer Promotions
Maximize marketing spend and stock levels for peak summer months.


3. Footwear-Led Strategy
Prioritize innovation, inventory, and advertising for the most profitable product line.


4. Optimize Operating Costs
Reduce costs in underperforming categories (e.g., Accessories) through renegotiated supplier contracts or bundle sales.


5. Expand in High-Performing Regions
Allocate more resources to regions like North America and explore similar markets.


6. Improve Wholesale Channel Margins
Review pricing strategy for wholesale partners and consider exclusive deals.




---

🗂️ Project Structure

adidas-sales-analysis/
│
├── data/
│   └── adidas_sales_dataset.csv
├── notebooks/
│   └── adidas_analysis.ipynb
├── visuals/
│   ├── sales_by_method.png
│   ├── monthly_sales_trend.png
│   ├── seasonal_heatmap.png
│   ├── product_sales_percent_pie.png
│   └── operating_profit_bar.png
├── README.md
└── requirements.txt


---

🛠️ Tools & Libraries

Python 3.x

Pandas, NumPy (Data manipulation)

Matplotlib, Seaborn, Plotly (Data visualization)

Jupyter Notebook

Optional: Streamlit for dashboard deployment