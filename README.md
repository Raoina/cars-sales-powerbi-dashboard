# car-sales-analytics
> A comprehensive Power BI report for exploring and visualizing car sales performance from 2022 to 2023.

## 📄 About the Dataset

This dataset includes customer and vehicle details for each sale:

| Column            | Description                            |
|-------------------|----------------------------------------|
| Car_id            | Unique identifier for each vehicle     |
| Date              | Sale date (YYYY-MM-DD)                 |
| Customer Name     | Buyer’s full name                      |
| Gender            | Buyer’s gender                         |
| Annual Income     | Buyer’s annual income in USD           |
| Dealer_Name       | Name of the selling dealership         |
| Company           | Car manufacturer                       |
| Model             | Specific vehicle model                 |
| Engine            | Engine capacity/type (e.g., 2.0L)      |
| Transmission      | Transmission type (Automatic/Manual)   |

---

## ✨ Key Features

- **📊 Sales Overview**  
  Total revenue, units sold, and average sale price.

- **📈 Monthly Trends**  
  Time-series line chart showing month-by-month sales growth.

- **🌍 Regional Insights**  
  Map visual displaying sales distribution across regions.

- **🏆 Model Performance**  
  Bar chart comparing top-selling makes and models.

- **⚙️ Engine & Transmission Analysis**  
  Slicers to filter by engine size and transmission type.

- **🔍 Outlier Detection**  
  DAX measures to flag unusually high or low sale amounts.

- **📑 KPI Cards**  
  High-level metrics for quick executive summary.

---

## 🚀 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/<your-username>/car-sales-analytics.git

## 🚀 Getting Started

1. **Open in Power BI Desktop**  
   - Open `CarSalesReport.pbix`.

2. **Configure Data Source**  
   - Place `car_sales_data.csv` in the same folder.  
   - In Power BI Desktop:  
     Home → Transform Data → Data source settings → Change source to this CSV.

3. **Publish to Power BI Service**  
   - In Power BI Desktop: File → Publish → To Power BI.  
   - Share with your team via Workspaces and assign Editor roles as needed.

## 📁 Repository Structure

- `CarSalesReport.pbix`      Main Power BI report  
- `data/`                    CSV data files  
  - `car_sales_data.csv`  
- `images/`                  Icons and screenshots  
- `README.md`                Project overview and setup  
- `.gitignore`               Files to ignore  

