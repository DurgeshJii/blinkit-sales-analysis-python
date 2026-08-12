# Blinkit Sales Data Analysis 📊

A Python-based exploratory data analysis project focused on understanding
sales performance across products, fat content, outlet sizes, outlet locations,
city tiers and establishment years.

## 🎯 Project Objective

The objective of this project is to transform raw Blinkit sales data into
meaningful business insights using Python-based data analysis and visualization.

## 📁 Dataset

The dataset contains:

- 8,523 records
- 12 columns
- Product information
- Outlet information
- Sales
- Ratings
- Item visibility
- Item weight

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔄 Analysis Workflow

1. Import libraries
2. Load raw dataset
3. Explore dataset structure
4. Check data types
5. Identify data-quality issues
6. Standardize categorical values
7. Calculate business KPIs
8. Perform grouped sales analysis
9. Create visualizations
10. Extract business insights

## 🧹 Data Cleaning

The `Item Fat Content` field contained inconsistent labels:

- `LF`
- `low fat`
- `Low Fat`
- `reg`
- `Regular`

These were standardized into:

- `Low Fat`
- `Regular`

## 📌 Key KPIs

| KPI | Result |
|---|---:|
| Total Sales | $1,201,681 |
| Average Sales | ~$141 |
| Unique Items | 1,559 |
| Average Rating | ~4.0 |

## 📊 Key Insights

### Fat Content

Low Fat products contributed approximately **64.6%** of total sales,
while Regular products contributed **35.4%**.

### Item Type

The highest-selling categories were:

1. Fruits and Vegetables — $178K
2. Snack Foods — $175K
3. Household — $136K
4. Frozen Foods — $119K
5. Dairy — $101K

### City Tier

Tier 3 locations generated the highest sales:

- Tier 3 — $472K
- Tier 2 — $393K
- Tier 1 — $336K

### Outlet Size

Medium outlets generated the highest share of sales:

- Medium — 42.3%
- Small — 37.0%
- High — 20.7%

### Outlet Establishment

Sales varied significantly across establishment years.
The 1998 outlets recorded the highest aggregate sales, while 2011
recorded the lowest.

However, establishment year should not be interpreted as a causal
factor because the number of outlets differs across years.

## 📈 Visualizations

The project includes visualizations for:

- Total Sales by Fat Content
- Total Sales by Item Type
- Fat Content across City Tiers
- Total Sales by Outlet Establishment Year
- Total Sales by Outlet Size
- Total Sales by Outlet Location

## 💡 Business Takeaways

The analysis suggests that:

- Low Fat products represent a major share of sales.
- Fruits & Vegetables and Snack Foods are important sales categories.
- Tier 3 locations are the largest contributor to total sales.
- Medium-sized outlets outperform High-sized outlets in aggregate sales.
- Sales performance should be evaluated using multiple outlet and product
  attributes rather than a single factor.

## 🚀 Future Improvements

Potential next steps:

- Add SQL-based analysis
- Build an interactive Power BI dashboard
- Perform statistical analysis
- Investigate missing Item Weight values
- Analyze sales by outlet type
- Study relationships between visibility, rating, weight and sales
- Build predictive models for sales forecasting

## 👨‍💻 Author

Durgesh Yadav

If you found this project useful, feel free to ⭐ the repository.
