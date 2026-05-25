# HR_Attrition Analytics Dashboard – Power BI Project

## 📌 Project Description
This project is an interactive **HR_Attrition Analytics Dashboard** created in **Power BI** to analyze employee attrition trends and workforce insights. The dashboard helps HR teams understand employee behavior, identify attrition patterns, and make data-driven decisions for improving employee retention and organizational performance.

The dashboard provides key HR metrics, demographic analysis, job role analysis, salary insights, and attrition trends through visual reports and KPIs.

---

# 🎯 Project Objective

The main objective of this project is to:

- Analyze employee attrition patterns within the organization.
- Identify key factors affecting employee turnover.
- Monitor workforce-related KPIs.
- Understand employee demographics and job role distribution.
- Help HR departments make strategic decisions using data visualization.
- Improve employee retention through actionable insights.

---

# 🛠 Tools & Technologies Used

- **Power BI Desktop**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- **Data Modeling**
- **Microsoft Excel / CSV Dataset**
- **Data Cleaning & Transformation**

---

# 📊 Dashboard KPIs

The dashboard includes the following key performance indicators:

### 1. Count of Employees
- Displays total number of employees in the organization.
- Value: **1470**

### 2. Attrition Count
- Shows total employees who left the company.
- Value: **237**

### 3. Attrition Rate
- Percentage of employees who left.
- Value: **16.1%**

### 4. Average Age
- Displays average age of employees.
- Value: **37 Years**

### 5. Average Salary
- Shows average employee salary.
- Value: **6.50K**

### 6. Average Years at Company
- Displays average years employees stay in the organization.
- Value: **7.01 Years**

---

# 📈 Charts and Visualizations Created

## 1. Attrition by Education (Donut Chart)
Shows employee attrition distribution according to education background.

Categories:
- Life Sciences
- Medical
- Marketing
- Technical Degree
- Other

Purpose:
- Identify which educational backgrounds have higher attrition.

---

## 2. Attrition by Age (Bar Chart)

Age Groups:
- 18–25
- 26–35
- 36–45
- 46–55
- 55+

Purpose:
- Analyze attrition patterns among different age groups.

---

## 3. Attrition by Gender (Tree Map)

Categories:
- Male
- Female

Purpose:
- Compare attrition distribution by gender.

---

## 4. Attrition by Salary Slab (Horizontal Bar Chart)

Salary Categories:
- Upto 5K
- 5K–10K
- 10K–15K
- 15K+

Purpose:
- Understand relationship between salary and employee attrition.

---

## 5. Attrition by Years at Company (Line/Area Chart)

Purpose:
- Analyze how employee experience impacts attrition.

---

## 6. Attrition by Job Role (Horizontal Bar Chart)

Job Roles:
- Laboratory Technician
- Sales Executive
- Research Scientist
- Sales Representative
- Human Resources

Purpose:
- Identify job roles with highest employee turnover.

---

## 7. Job Role Matrix Table

Displays:
- Attrition distribution by job roles and categories.

Purpose:
- Detailed comparison and role-level insights.

---

# 🔄 Complete Project Process

## Step 1: Data Collection
- Collected HR employee dataset.
- Imported dataset into Power BI.

## Step 2: Data Cleaning
Performed data cleaning using Power Query:

- Removed duplicate values
- Checked missing values
- Corrected data types
- Renamed columns
- Removed unnecessary fields

---

## Step 3: Data Transformation
- Structured data for analysis
- Created calculated columns
- Created measures using DAX

Examples:

**Attrition Rate Measure**

```DAX
Attrition Rate =
DIVIDE([Attrition Count],[Employee Count])*100
```

**Average Salary**

```DAX
Average Salary =
AVERAGE(Employee[MonthlyIncome])
```

---

## Step 4: Data Modeling

- Built relationships between tables
- Optimized data structure
- Applied filtering logic

---

## Step 5: Dashboard Design

Created dashboard layout including:

- KPI cards
- Charts
- Matrix visualization
- Department filters
- Interactive reports

---

## 📌 Project Insights

### Employee Insights

- Total employee count is **1470**.
- Total attrition count is **237 employees**.
- Overall attrition rate is **16.1%**.

### Age-Based Insights

- Employees in the **26–35 age group** have the highest attrition.
- Senior employees have comparatively lower attrition rates.

### Salary Insights

- Employees with salary **up to 5K** show maximum attrition.
- Attrition decreases as salary increases.

### Education Insights

- Employees from **Life Sciences** contribute the highest attrition percentage.
- Technical Degree and Marketing categories have lower attrition.

### Job Role Insights

- **Laboratory Technician** has highest attrition.
- **Sales Executive** and **Research Scientist** also show significant attrition.
- Human Resources has lower attrition.

### Gender Insights

- Male employee attrition is higher compared to female employees.

### Experience Insights

- Employees with fewer years in the company are more likely to leave.

---

# 📋 Business Recommendations

Based on dashboard insights:

- Improve retention strategies for employees in the 26–35 age group.
- Review salary structures for lower salary bands.
- Focus on high attrition job roles.
- Increase employee engagement programs.
- Develop better career growth opportunities.
- Strengthen onboarding and employee satisfaction initiatives.

---

# ✅ Final Conclusion

The HR Analytics Dashboard successfully provides a comprehensive analysis of employee attrition and workforce behavior. Through Power BI visualizations and KPI metrics, important patterns related to age, salary, education, gender, and job roles were identified.

This dashboard helps HR teams make informed decisions, reduce attrition rates, and improve employee retention strategies using data-driven insights.

---
## HR_Attrition Dashboard Dataset (MS Excel)
<a href="">Data_set</a>

## 📷 Dashboard Preview
<a href="https://github.com/harmishaborisaniya-cloud/HR_Attrition_-powerBi_dashboard/blob/main/HR.png">Screenshort</a>

---

## 👨‍💻 Author
Harmisha Borisaniya


