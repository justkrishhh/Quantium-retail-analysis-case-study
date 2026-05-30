# Quantium-retail-analysis-case-study
## 📌 Project Overview

This project focuses on analyzing customer purchasing behavior and evaluating the effectiveness of retail store trial layouts using transaction and customer purchase data from a supermarket chips category.

The analysis was conducted as part of a retail analytics case study to help the Category Manager develop a strategic plan for the upcoming half year.

The project combines:

- Customer segmentation analysis
- Purchasing behavior analysis
- Trial vs Control store experimentation
- Statistical significance testing
- Business recommendations using data-driven insights

---

# 🎯 Business Problem

A supermarket Category Manager wanted to understand:

1. **Who purchases chips and what drives their purchasing behavior**
2. **Which customer segments contribute most to sales**
3. **Whether newly introduced trial store layouts improved performance**
4. **If the trial layout should be rolled out to all stores**

The objective was to generate actionable business recommendations supported by analytics.

---

# 📂 Project Structure

## Task 1 — Customer & Transaction Analytics

### Objective
Understand customer purchasing behavior and identify the key drivers of chip sales.

### Key Activities

### 1. Data Cleaning & Validation
- Checked for missing values and inconsistencies
- Removed anomalies and outliers
- Verified numerical formats
- Ensured proper category identification

### 2. Data Merging
Combined:

- Transaction dataset
- Customer purchase behavior dataset

using loyalty card numbers for customer-level analysis.

### 3. Feature Engineering
Created additional variables such as:

- **Pack size extraction**
- **Brand name extraction**
- **Monthly purchase tracking**
- **Customer segmentation metrics**

### 4. Customer Segmentation Analysis
Analyzed purchasing patterns based on:

#### Life Stage
Examples:
- Young Singles/Couples
- Families
- Older Families
- Retirees

#### Premium Customer Type
- Budget
- Mainstream
- Premium

### Key Metrics Analyzed
- Total Sales Revenue
- Customer Count
- Transactions per Customer
- Average Spend per Transaction
- Brand Preferences
- Pack Size Preferences

### Key Findings
- **Mainstream Young Singles/Couples** generated the highest chip sales.
- **Budget Families** contributed strongly to sales volume.
- **Premium customers** demonstrated higher spending per transaction.
- Customer purchasing behavior varied significantly across life stage and spending profile.

### Business Recommendation
Target high-value customer segments through personalized promotions and optimize product offerings based on purchasing behavior.

---

## Task 2 — Trial Store Performance Analysis

### Objective
Evaluate whether new trial store layouts improved performance in selected stores.

### Trial Stores
- Store **77**
- Store **86**
- Store **88**

### Methodology

### 1. Control Store Selection
Selected control stores based on historical similarity using:

- Total Sales Revenue
- Number of Customers
- Transactions per Customer

### Similarity Measurement
Applied:

#### Pearson Correlation Analysis
to identify stores with the closest historical purchasing behavior during the pre-trial period.

### 2. Trial vs Control Analysis
Compared:

- Monthly Sales Trends
- Customer Growth
- Transactions per Customer

between:

**Trial stores vs matched control stores**

### 3. Statistical Testing
Performed statistical significance testing using:

#### Independent T-Test

to determine whether observed sales changes during the trial period were statistically meaningful.

### Results

#### Store 77
✅ Statistically significant improvement

**P-value:** 0.000065

#### Store 86
❌ No statistically significant improvement

**P-value:** 0.311

#### Store 88
✅ Statistically significant improvement

**P-value:** 0.0000016

### Key Insight
The trial layout improved performance in **2 out of 3 stores**, indicating strong potential for selective rollout.

### Business Recommendation
- Roll out the new layout to stores similar to **77** and **88**
- Conduct further testing for stores resembling **86**
- Use targeted deployment rather than full-scale rollout

---

## Task 3 — Business Presentation & Strategic Recommendations

### Objective
Translate analytical findings into a business-friendly client presentation.

### Deliverables
Developed a consulting-style report including:

- Executive Summary
- Customer Insights
- Purchasing Behavior Analysis
- Trial Store Evaluation
- Strategic Recommendations
- Next Steps

### Approach
Applied the **Pyramid Principle Framework** to structure insights in a concise and executive-friendly format.

### Key Recommendation
A **selective rollout strategy** is recommended based on trial store performance and customer purchasing behavior insights.

---

# 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Excel**
- **Statistical Testing**

---

# 📈 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Customer Segmentation
- Retail Analytics
- A/B Testing
- Trial vs Control Analysis
- Statistical Significance Testing
- Business Intelligence
- Data Visualization
- Stakeholder Reporting

---

# 🚀 Business Impact

This analysis identified high-value customer segments and demonstrated statistically significant performance uplift in **2 out of 3 trial stores**, supporting **data-driven retail decision-making and selective store rollout strategies**.

---

## 👨‍💻 Author

**Krish Gupta**  
Aspiring Data Analyst | Python | SQL | Power BI | Excel
