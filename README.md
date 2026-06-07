# 🔷 CodTech IT Solutions — Internship Task 1
## Big Data Analysis using Dask

---

## 👤 Intern Details

| Field | Details |
|---|---|
| **Intern Name** | Ankit Kumar Pradhan|
| **Intern ID** | CITS442 |
| **Company** | CodTech IT Solutions Pvt. Ltd |
| **Domain** | Data Analytics |
| **Task** | Task-1: Big Data Analysis |
| **Tool Used** | Dask (scalable big data processing) |
| **Dataset** | E-Commerce Sales Dataset (India) |
| **Mentor** | Neela Santhosh Kumar |
| **Duration** | 4 Weeks |

---

## 📌 Task Overview

This task involves performing **Big Data Analysis** on a large e-commerce sales dataset using scalable data processing tools. The goal is to demonstrate the ability to handle large datasets efficiently using **Dask**, derive meaningful business insights, and visualize the results.

**Task Requirement (as given by CodTech):**
> Perform analysis on a large dataset using tools like PySpark or Dask to demonstrate scalability. Deliverable: A script or notebook with insights derived from big data processing.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| **Python 3.x** | Core programming language |
| **Dask** | Scalable big data processing (parallel/lazy evaluation) |
| **Pandas** | Data manipulation after Dask computation |
| **Matplotlib** | Data visualizations and charts |
| **Seaborn** | Statistical plotting |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📂 Files in This Repository

```
Task1-Big-Data-Analysis/
│
├── Task1_Big_Data_Analysis.ipynb   ← Main Jupyter Notebook (analysis + insights)
├── ecommerce_sales_data.csv        ← Dataset used for analysis
└── README.md                       ← This file
```

---

## 📊 Dataset Description

**File:** `ecommerce_sales_data.csv`  
**Domain:** E-Commerce Sales (India)  
**Records:** 100 orders  
**Columns:** 20 features

| Column | Description |
|---|---|
| `order_id` | Unique order identifier |
| `customer_id` | Unique customer identifier |
| `customer_name` | Full name of customer |
| `customer_age` | Age of the customer |
| `customer_gender` | Male / Female |
| `customer_city` | City of delivery |
| `customer_state` | State of delivery |
| `product_id` | Unique product identifier |
| `product_name` | Name of the product |
| `category` | Product category (Electronics, Fashion, etc.) |
| `sub_category` | Product sub-category |
| `brand` | Product brand |
| `unit_price` | Price per unit (₹) |
| `quantity` | Number of units ordered |
| `discount_percent` | Discount applied (%) |
| `order_date` | Date of order |
| `order_status` | Delivered / Returned / Cancelled |
| `payment_method` | UPI / Credit Card / Debit Card / EMI |
| `shipping_days` | Days taken to deliver |
| `rating` | Customer rating (1–5) |

---

## 🔑 Key Features of the Analysis

- ✅ **Dask lazy loading** — dataset loaded without reading into memory upfront
- ✅ **Dask GroupBy** — scalable aggregations (groupby, sum, mean) on large data
- ✅ **Data Cleaning** — null checks, date parsing, derived column creation
- ✅ **EDA (Exploratory Data Analysis)** — statistical summaries and distributions
- ✅ **Business Insights** — revenue by category, state, monthly trends
- ✅ **Visualizations** — 6 professional charts saved as PNG files

---

## 📈 Insights Derived

1. **Electronics** is the highest revenue-generating product category
2. **Maharashtra, Delhi & Karnataka** are the top revenue states
3. **UPI** is the most preferred payment method (digital-first India)
4. **~85% order delivery rate** with low return/cancellation rate
5. **Average customer rating: 4.0+ / 5.0** — high satisfaction
6. **Revenue shows upward monthly trend** (Jan–May 2024)
7. **Dask scales seamlessly** to GB/TB datasets without code changes

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2. Install Dependencies
```bash
pip install dask pandas matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook Task1_Big_Data_Analysis.ipynb
```

### 4. Run All Cells
- Go to **Kernel → Restart & Run All**
- All charts will be generated and saved automatically

---

## 📦 Output Charts Generated

| Chart File | Description |
|---|---|
| `order_status_distribution.png` | Pie chart of Delivered / Returned / Cancelled |
| `revenue_by_category.png` | Horizontal bar chart of revenue per category |
| `monthly_revenue_trend.png` | Line chart of monthly revenue trend |
| `top5_states_revenue.png` | Bar chart of top 5 states by revenue |
| `payment_method_usage.png` | Bar chart of payment method preferences |
| `rating_distribution.png` | Bar chart of customer ratings |

---

## 🙏 Acknowledgement

This task was completed as part of the **Data Analytics Internship** at **CodTech IT Solutions Pvt. Ltd.**  
I thank my mentor and the CodTech team for the guidance and opportunity.

---

*© 2024 CodTech IT Solutions | Data Analytics Internship*
