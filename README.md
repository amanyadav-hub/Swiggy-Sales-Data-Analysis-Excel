# Swiggy-Sales-Data-Analysis-Excel
Exploratory Data Analysis of Swiggy food delivery data using Excel — covering city-wise orders, restaurant performance, pricing, ratings, and an interactive dashboard.
# 🍔 Swiggy Sales Data Analysis — Excel & Dashboard

## 📌 Project Overview

This project performs a complete **Exploratory Data Analysis (EDA)** on Swiggy food delivery order data using **Microsoft Excel**. It covers data cleaning, feature engineering, pivot-based analysis, and an interactive **Excel Dashboard** to visualize key business insights across restaurants, cities, categories, ratings, and pricing.

---

## 📂 Repository Files

| File | Description |
|---|---|
| `Swiggy_Raw_Data_Excel.xlsx` | Raw dataset with 1,97,430 Swiggy orders across India |
| `Swiggy_Dashboard_and_Analysis.xlsb` | Cleaned data + pivot analysis + interactive Excel Dashboard |

---

## 📊 Dataset Description

**File:** `Swiggy_Raw_Data_Excel.xlsx`  
**Sheet:** `Swiggy Data`  
**Total Records:** 1,97,430 rows

| Column | Description |
|---|---|
| State | Indian state of the order |
| City | City where the order was placed |
| Order Date | Date of the order (Jan 2025 – Aug 2025) |
| Restaurant Name | Name of the restaurant |
| Location | Locality/area within the city |
| Category | Food category/menu section |
| Dish Name | Name of the dish ordered |
| Price (INR) | Price of the dish in Indian Rupees |
| Rating | Restaurant/dish rating (1.5 – 5.0) |
| Rating Count | Number of customer ratings |

---

## 🌍 Data Coverage

- **28 States** across India
- **28 Cities** including Bengaluru, Mumbai, Hyderabad, Jaipur, Lucknow, Delhi, and more
- **993 Unique Restaurants**
- **Price Range:** ₹0.95 to ₹8,000
- **Time Period:** January 2025 – August 2025

---

## 🛠️ Tools & Technologies

- **Tool:** Microsoft Excel (`.xlsx` + `.xlsb`)
- **Techniques Used:** Data Cleaning, Pivot Tables, Conditional Formatting, Charts, Slicers, Dashboard Design

---

## 🔍 Analysis Performed

### 📦 Product & Category Analysis
- Most ordered food categories across cities
- Top-performing dish names by order volume
- Category-wise average price distribution

### 🏙️ City & Location Insights
- Cities with the highest number of orders
- State-wise order distribution
- Top localities by restaurant density

### 🍽️ Restaurant Performance
- Highest-rated restaurants
- Restaurants with maximum orders
- Average rating vs. rating count comparison

### 💰 Pricing Analysis
- Average dish price by city and category
- Price range segmentation (budget, mid-range, premium)
- Correlation between price and rating

### ⭐ Rating Analysis
- Distribution of ratings across all orders
- Low-rated vs. high-rated category breakdown
- Rating trends by city and restaurant type

---

## 📈 Dashboard Highlights

The `Swiggy_Dashboard_and_Analysis.xlsb` file contains an **interactive Excel Dashboard** featuring:

- 📊 **Bar Charts** — Top cities by order count
- 🥧 **Pie/Donut Charts** — Category-wise share of orders
- 📉 **Line/Trend Charts** — Monthly order trends
- 🔢 **KPI Cards** — Total orders, avg price, avg rating, total restaurants
- 🎛️ **Slicers** — Filter by City, State, Category, and Rating

---

## 🚀 How to Use

1. **Download both files** from this repository.
2. Open `Swiggy_Raw_Data_Excel.xlsx` to explore the raw data.
3. Open `Swiggy_Dashboard_and_Analysis.xlsb` in **Microsoft Excel** (recommended: Excel 2016 or later).
4. Use the **slicers/filters** on the dashboard to interact with the charts.
5. Navigate to the analysis sheets to explore pivot tables and supporting charts.

> ⚠️ **Note:** The `.xlsb` file is in Excel Binary Workbook format. Open with Microsoft Excel for best compatibility. Google Sheets may not fully support all features.

---

## 💡 Key Insights (Summary)

- **Bengaluru** had the highest number of orders (20,077), followed by Mumbai and Hyderabad.
- **Recommended** was the most common category, indicating Swiggy's algorithmically promoted dishes drive a large share of orders.
- Average dish prices vary significantly across cities, with metro cities showing higher mid-range pricing.
- Most restaurants maintained ratings between **3.5 and 4.5**, with very few below 2.5.
- **January and March 2025** saw peak ordering activity in the dataset period.

---

## 📁 Repository Structure

```
Swiggy-Sales-Data-Analysis-Excel/
│
├── Swiggy_Raw_Data_Excel.xlsx           # Raw Swiggy orders dataset
├── Swiggy_Dashboard_and_Analysis.xlsb  # Analysis + Dashboard (Excel)
└── README.md                            # Project documentation
```

---

## 🙋‍♂️ Author

**[Aman Yadav]**  
Aspiring Data Analyst | Excel | MySQL | Power BI  
📧 [amanyadav11981@gmail.com]  
🔗 [[LinkedIn Profile URL](https://www.linkedin.com/in/aman-yadav-a1a5b8216)]

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
