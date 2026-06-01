# Marketing A/B Testing Analytics

## Project Overview

This project analyzes the effectiveness of a marketing campaign using A/B Testing techniques. The objective is to determine whether displaying advertisements ("Ad" group) leads to higher conversion rates compared to the Public Service Announcement ("PSA" group).

The project follows a complete Data Analytics workflow, including data cleaning, exploratory data analysis (EDA), SQL-based business analysis, statistical testing, regression analysis, and interactive dashboard development in Power BI.

---

## Dataset Information

- Total Records: 588,101
- Features: 7
- Source: Kaggle Marketing A/B Testing Dataset

### Dataset Columns

| Column | Description |
|----------|-------------|
| user_id | Unique user identifier |
| test_group | Ad or PSA group |
| converted | Whether the user converted |
| total_ads | Total ads viewed |
| most_ads_day | Day with maximum ad exposure |
| most_ads_hour | Hour with maximum ad exposure |

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-Learn
- PostgreSQL
- SQLAlchemy
- Power BI
- Git & GitHub

---

## Project Workflow

### 1. Data Preparation & Cleaning
- Loaded dataset using Pandas
- Verified data types and structure
- Checked for missing values
- Removed unnecessary columns
- Standardized column names
- Performed data quality validation

### 2. Exploratory Data Analysis (EDA)
- Conversion rate analysis
- Distribution of ad exposure
- Day-wise conversion analysis
- Hour-wise conversion analysis
- Ad exposure impact on conversions
- User behavior exploration

### 3. PostgreSQL Analysis
The cleaned dataset was loaded into PostgreSQL for business analysis.

Key business questions answered:

1. Conversion Rate by Test Group
2. Total Users by Group
3. Average Ads Viewed by Group
4. Conversion Rate by Day
5. Conversion Rate by Hour
6. Ad Exposure vs Conversion
7. Top Performing Days
8. Top Performing Hours
9. Subscriber Behavior Analysis
10. User Segmentation
11. Campaign Performance Metrics
12. Revenue/Conversion Insights

### 4. A/B Testing
Performed statistical hypothesis testing to determine whether the Ad group significantly outperformed the PSA group.

#### Hypotheses

**Null Hypothesis (H₀):**
There is no significant difference in conversion rates between the Ad and PSA groups.

**Alternative Hypothesis (H₁):**
The Ad group has a significantly different conversion rate compared to the PSA group.

### 5. Regression Analysis
Built a regression model to understand the relationship between ad exposure and user conversion behavior.

Key variables analyzed:
- Total Ads Viewed
- Most Active Day
- Most Active Hour
- Test Group

### 6. Power BI Dashboard
Created an interactive dashboard to communicate business insights.

Dashboard Components:
- Total Users
- Total Conversions
- Conversion Rate
- Average Ads Seen
- Ad vs PSA Performance
- Conversion Rate by Day
- Conversion Rate by Hour
- Conversion Rate by Ad Exposure
- Interactive Filters
- Business Recommendations

---

## Key Insights

- The Ad group achieved a higher conversion rate than the PSA group.
- Conversion rates varied significantly across different days and hours.
- Users exposed to more advertisements generally showed higher conversion rates.
- Certain time periods demonstrated stronger campaign effectiveness.
- Ad exposure played an important role in influencing user conversions.

---

## Business Recommendations

- Increase ad spending during high-converting hours.
- Optimize campaign scheduling based on top-performing days.
- Improve targeting strategies for users with higher engagement.
- Continuously monitor campaign effectiveness using A/B testing.
- Use data-driven decisions to maximize conversion rates and marketing ROI.

---

## Dashboard Preview

Add your Power BI dashboard screenshot below:

![Dashboard Preview](images/dashboard_screenshot.png)

---

## Repository Structure

```text
marketing-ab-testing-analytics/
│
├── data/
│   └── marketing_AB.csv
│
├── notebooks/
│   └── marketing_analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── dashboard/
│   └── marketing_dashboard.pbix
│
├── images/
│   └── dashboard_screenshot.png
│
├── README.md
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/marketing-ab-testing-analytics.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/marketing_analysis.ipynb
```

---

## Author

**Uday Kumar Saroj**

Aspiring Data Analyst | Python | SQL | PostgreSQL | Power BI | Statistics | A/B Testing
