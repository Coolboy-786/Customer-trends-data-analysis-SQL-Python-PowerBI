# 📊 Customer Shopping Behavior Analysis – README

## 1. Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product preferences, and subscription trends.

The workflow covers data loading in Python, exploratory data analysis (EDA), data cleaning, SQL-based analysis, and visualization through a Power BI dashboard. The final deliverables include a report and presentation.

---

## 2. Dataset

* **Rows:** ~3,900

* **Columns:** 18

* **Key Features:**

  * Customer demographics (age, gender, location, subscription status)
  * Purchase details (item, category, amount, season, size, color)
  * Behavioral data (discount usage, purchase frequency, ratings, shipping type)

* **Data Quality:**

  * Missing values in `review_rating` handled using median imputation

---

## 3. Tools & Technologies

* **Python:** pandas, numpy (data processing & EDA)
* **SQL:** PostgreSQL / MySQL / SQL Server (analysis queries)
* **Power BI:** dashboard creation
* **Jupyter Notebook:** development environment
* **PowerPoint:** presentation of insights

---

## 4. Steps

### A. Data Preparation (Python)

* Load dataset using pandas
* Explore structure (`.info()`, `.describe()`)
* Handle missing values
* Standardize column names (snake_case)
* Perform feature engineering:

  * Age groups
  * Purchase frequency
* Remove redundant columns
* Export cleaned data to SQL database

### B. Data Analysis (SQL)

Key business questions answered:

* Revenue by gender
* High-spending discount users
* Top-rated products
* Shipping type comparison
* Subscriber vs non-subscriber behavior
* Customer segmentation (New, Returning, Loyal)
* Revenue by age group
* Top products per category

### C. Dashboard (Power BI)

* Interactive visualizations
* KPIs (Revenue, Avg Spend, Customer Segments)
* Filters for demographics and purchase behavior

---

## 5. Results

* Identified high-value customer segments
* Discovered top-performing products and categories
* Found correlation between discounts and spending
* Observed differences in subscriber vs non-subscriber behavior
* Highlighted key revenue-driving demographics

---

## 6. Business Recommendations

* Promote subscription benefits to increase retention
* Introduce loyalty programs for repeat customers
* Optimize discount strategies for profitability
* Focus marketing on high-value segments
* Highlight top-rated products in campaigns

---

## 7. How to Run

### Step 1: Clone Repository

```bash
git clone <your-repo-link>
cd <project-folder>
```

### Step 2: Run Python Analysis

```bash
pip install -r requirements.txt
jupyter notebook
```

* Open and run `data_analysis.ipynb`

### Step 3: Load Data into SQL

* Connect Python to your database
* Export cleaned dataset
* Run SQL scripts from `/sql` folder

### Step 4: Open Dashboard

* Launch Power BI
* Open `.pbix` file

### Step 5: View Presentation

* Open the PowerPoint file for summary insights

---

## 8. Project Structure

```
├── data/
├── notebooks/
│   └── data_analysis.ipynb
├── sql/
├── dashboard/
│   └── powerbi.pbix
├── reports/
│   └── report.pdf
├── presentation/
│   └── slides.pptx
└── README.md
```

---

## 9. Contact

For questions or collaboration, feel free to reach out.

---

**Simple. Clear. Recruiter-friendly.**
