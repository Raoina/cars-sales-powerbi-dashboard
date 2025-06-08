<p align="center">
  <img src="images/cover.png" width="100%" />
</p>

# 🚗 Car Sales Analytics Dashboard

A professional **Power BI dashboard** built to explore and visualize car sales performance between **January 2022 and December 2023**, helping stakeholders make data-driven decisions in the automotive industry.

---

## 📊 Project Objective

This dashboard aims to deliver actionable insights into:
- Car sales performance over time
- Customer preferences (e.g., gender, income)
- Regional sales patterns
- Top-selling models and companies
- Impact of engine size, transmission, and color on sales

---

## 🧾 Dataset Overview

The dataset contains **23,906 car sales records** with the following fields:

| Column            | Description                             |
|-------------------|-----------------------------------------|
| Car_id            | Unique ID for each vehicle              |
| Date              | Sale date (YYYY-MM-DD)                  |
| Customer Name     | Buyer’s full name                       |
| Gender            | Buyer’s gender                          |
| Annual Income     | Buyer’s income in USD                   |
| Dealer_Name       | Name of the selling dealership          |
| Company           | Car manufacturer                        |
| Model             | Specific vehicle model                  |
| Engine            | Engine capacity/type (e.g., 2.0L)       |
| Transmission      | Manual / Automatic                      |
| Color             | Vehicle color                           |
| Price             | Sale price in USD                       |
| Body Style        | SUV, Sedan, Hatchback, etc.             |
| Dealer Region     | Geographic location of dealer           |

📌 **Summary**:
- 💼 30 unique companies
- 🚘 154 unique models
- 💰 Total sales ≈ $672 million
- 🔄 Cars sold: 24,000+

---

## 🧹 Data Preprocessing

- ✅ Cleaned and converted `Date` fields for time-series analysis
- 🧠 Categorized `Price` into: Affordable / Mid-Range / Premium
- 🔁 Standardized categorical values (Gender, Transmission, Region)
- 📊 Validated distribution of key fields (Region, Brand, Style)
- 🧽 Removed duplicates and formatted text fields

---

## 📈 Dashboard Features

- 🏁 **Sales Overview**: Total sales, units sold, and average price (KPI cards)
- 📆 **Monthly Trends**: Time-series visual showing sales growth
- 🌍 **Regional Insights**: Map displaying distribution across regions
- 🏎️ **Top Models**: Best-selling brands and models
- ⚙️ **Engine & Transmission**: Interactive filters and comparisons
- 🎯 **Customer Segmentation**: Gender and income-based slicing
- 🚨 **Outlier Detection**: Identifies unusually high/low sales
- 📌 **Color & Style Preferences**: Visual breakdowns by color & body style

---

## 📦 Repository Structure

```
├── CarSalesReport.pbix         # Power BI report file
├── data/
│   └── car_sales_data.csv      # Main dataset
├── images/                     # Screenshots & assets
└── README.md                   # Project overview (this file)
```

---

## ⚙️ Getting Started

1. **Clone the Repo**
   ```bash
   git clone https://github.com/Raoina/powerbi-dashboard
   ```
2. **Open Power BI File**
   - Launch `CarSalesReport.pbix` using Power BI Desktop

3. **Connect the Dataset**
   - Place `car_sales_data.csv` in the same folder
   - Go to: `Home` → `Transform Data` → `Data source settings` → Change Source

4. **Publish Online**
   - In Power BI: `File` → `Publish` → `To Power BI Service`

---

## 💡 Business Recommendations

Based on the dashboard insights, here are some recommendations:

- 🎯 **Target High-Income Customers**: Premium vehicles show higher conversions among high earners.
- 🧍 **Gender-Based Campaigns**: Identify gender preferences per model to design targeted ads.
- 🗺️ **Regional Marketing**: Boost promotions in underperforming regions.
- 🏁 **Top Models Focus**: Allocate inventory towards best-selling models and brands.
- 🛠️ **Optimize Transmission Offering**: Trends show strong preferences for automatic over manual.
- 🎨 **Color Trends**: Leverage insights about popular colors for inventory planning.

---

## 📬 Contact

Made with ❤️ by [Rowaina Reda](https://www.linkedin.com/in/rowaina-reda)

📧 Email: roainareda@gmail.com  
📍 Location: Alexandria, Egypt

---
