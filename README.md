# customer-churn-reduction
Analyzing the telecom company called Databel's dataset to identify the customer churn patterns and make recommendations to reduce it.

Analyzing churn doesn’t just mean knowing what the churn rate is: it’s also about figuring out why customers are churning at the rate they are, and how to reduce churn.

## 📝 Project Overview
A data‑driven investigation into customer churn patterns, leveraging SQL for data extraction and transformation, Tableau for interactive dashboarding, and core data analysis techniques to uncover insights and recommend retention strategies.
This dashboard was built to analyze the underlying data, identify key drivers of churn, and provide actionable recommendations to reduce attrition and improve customer retention.

## 🔧 Technologies & Tools
- **SQL** (MySQL / PostgreSQL / Snowflake etc.) for data wrangling, aggregation, and modeling  
- **Tableau** for dashboard creation and visual storytelling  
- **Python** for supplemental analysis and automation scripts  
- **Git** for version control

## 📊 Data Source & Preparation
1. **Source**:  Databel - Data file 
2. **Key Tables/Fields**:  
   - Customer Data (6687 rows × 29 fields)
3. **Preprocessing Steps**:  
   - Handle missing values (e.g. impute or drop)  
   - Normalize data types (dates, categories)  
   - Feature engineering: Tenure months, average usage, support calls count
  
## **Key Metrics**:  
  - Total Customers: 6687  
  - Churned Customers: 1796  
  - Churn Rate: 26.86%
  
## 🛠️ SQL Analysis

## 📈 Tableau Dashboards
1. **Overview Dashboard** – High‑level churn and retention trends over time
2. **Churn Reasons Visualization** – Breakdown of churn counts by reason category
3. **Churn by State** – Geospatial map highlighting state‑level churn rates  
4. **Churn by Category** – Bar/column charts comparing churn across service or demographic segments 
5. **Churn by Age Bins** – Analysis of churn rates across predefined age groups 

## Key Findings & Recommendations
- **Focus on California**: highest churn concentration; prioritize targeted retention offers there.  
- **Competitive Offers**: tailor promotional packages to undercut competitors.  
- **Age‑Group Targeting**: develop engagement strategies for age bins with elevated churn rates
