# Syntecxhub Sales Analysis
Data Science Week 4 Task 1\
Author: Debojit Roy Chowdhury

**Resources:**
* Dataset (Kaggle) - https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset?select=SampleSuperstore.csv
* Pandas - https://pandas.pydata.org/docs/
* Seaborn Visuals - https://seaborn.pydata.org/
* Matplot Library - https://matplotlib.org/stable/gallery/index.html

------

## Overview
This project focuses on analyzing retail sales data to extract meaningful business insights. Using data analysis and visualization techniques, the project explores sales trends, identifies top-performing products and regions, and computes key performance indicators (KPIs) to support data-driven decision making.

## Objectives
* Analyze retail sales data to answer business questions
* Identify top-selling products and seasonal trends
* Compute key performance indicators (KPIs)
* Visualize trends and comparisons using charts
* Provide actionable business recommendations

## Dataset

The dataset used is a retail sales dataset (Sample Superstore), which includes:
* Order Date
* Product Name
* Category / Sub-Category
* Sales
* Region
* Quantity, Discount, Profit

The dataset is suitable for analyzing sales performance, trends, and business metrics.

## Technologies Used
* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Key Analysis

### Data Preparation
* Converted `Order Date` to datetime format
* Extracted monthly data for trend analysis

### Key Performance Indicators (KPIs)
* **Total Revenue** → Total sales generated
* **Average Order Value (AOV)** → Average revenue per order
* **Top Regions** → Regions contributing highest sales

### Sales Trend Analysis
* Monthly aggregation of sales
* Line chart used to visualize seasonality and trends

### Top Products Analysis
* Identified top 10 products based on sales
* Used bar chart for comparison

### Regional Analysis
* Compared sales across different regions
* Identified high and low performing regions

### Category Analysis
* Visualized sales distribution across categories using pie chart

## Visualizations
The following visualizations were created and saved:
* Monthly Sales Trend (Line Chart)
* Top Products by Sales (Bar Chart)
* Sales by Region (Bar Chart)
* Category Distribution (Pie Chart)

## Key Insights
* Sales exhibit noticeable seasonal trends across months
* A small number of products contribute significantly to total revenue
* Certain regions consistently outperform others
* Sales distribution is dominated by specific product categories

## Recommendations
* Focus marketing and inventory efforts on top-performing products
* Improve strategies in lower-performing regions
* Plan inventory and promotions based on seasonal demand patterns
* Expand high-performing categories to maximize revenue

## How to Run the Project
1. Clone the repository:

```bash
git clone https://github.com/DebojitRC/Syntecxhub_Sales_Analysis.git
```

2. Navigate to the project folder:

```bash
cd Syntecxhub_Sales_Analysis
```

3. Install required libraries:

```bash
pip install pandas matplotlib seaborn
```

4. Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Scope
* Perform deeper analysis using customer segmentation
* Build dashboards using Power BI or Tableau
* Apply predictive analysis for sales forecasting

## Conclusion
This project demonstrates how retail sales data can be analyzed to derive actionable business insights. By combining KPIs with visualization, organizations can make informed decisions to improve performance and profitability.
