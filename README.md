<div align="center">

# 🏢 IBM HR Analytics Dashboard

### *Turning workforce data into talent intelligence*

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![HR Analytics](https://img.shields.io/badge/HR_Analytics-0078D4?style=for-the-badge&logo=databricks&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

<br>

> **An interactive Tableau dashboard that decodes the story behind 1,470 IBM employees —  
> who's leaving, why they're leaving, and what HR can do about it.**

<br>

**Built by [Nidhish Kamboj](https://github.com/nidhishkamboj)**

---

</div>

## 🖼️ Full Dashboard Overview

![IBM HR Analytics Dashboard](Images/IBM_Dashboard.png)

> *The complete dashboard — 8 interactive views in one place, powered by the IBM HR Employee Attrition dataset.*

---

## 🎯 Why This Project?

Every time an employee walks out the door, the organization loses an average of **6–9 months' salary** in recruitment and training costs. For a 1,470-person company, even a modest attrition rate has massive financial consequences.

This dashboard was built to answer the questions HR leaders actually care about:

- 📌 Which departments are bleeding talent?
- 📌 Does pay gap drive people to leave?
- 📌 Are younger employees less loyal — or just undervalued?
- 📌 What does the gender breakdown tell us about culture?

---

## 📊 Dashboard Deep Dive

### 1. 🧑‍🤝‍🧑 Gender Split in the Company

![Gender in the Company](Images/Gender_in_the_Company.png)

The workforce skews **60% male and 40% female** — a notable gap that raises questions about representation, especially in senior roles. Cross-referencing this with job roles and compensation helps surface whether the gap is structural or role-driven.

---

### 2. 💍 Gender & Marital Status Breakdown

![Gender and Marital Status](Images/Gender_and_Marital_Status.png)

The largest single segment is **Married Males (401 employees)**, followed closely by **Married Females (272)** and **Single Males (271)**. This treemap reveals that single employees — who tend to have fewer personal anchors — could represent a higher flight-risk group worth monitoring for attrition.

---

### 3. 👔 Job Role Distribution by Gender

![Job Role and Gender](Images/Job_Role_and_Gender.png)

Across every job role, males outnumber females. The gap is sharpest in **Laboratory Technician** (174M vs 85F) and **Sales Executive** (194M vs 132F). Notably, **Research Scientist** is the most populous role overall with 292 combined employees — making retention there a high-priority concern.

---

### 4. 🏗️ Total Employees by Job Role & Department

![Total Employees by Job Role and Department](Images/Total_employees_by_Job_role_and_Department.png)

Research & Development dominates headcount, with **Research Scientists (292)**, **Laboratory Technicians (259)**, and **Manufacturing Directors (145)** making up the bulk. Sales Executives (326) form the single largest role company-wide. HR is the leanest department with only 63 total employees across two roles.

---

### 5. 🎓 Workforce Education Profile

![Total Employees by Education Field](Images/Total_Employees_by_Education_Field.png)

The talent pool is heavily concentrated in **Life Sciences (606)** and **Medical (464)** backgrounds — together accounting for over **73% of all employees**. This reflects IBM's R&D-heavy focus. Marketing (159) and Technical Degree (132) are the next largest pools, while Human Resources grads represent just 27 employees.

---

### 6. 🎂 Average Age by Department & Job Role

![Average Age by Department and Job Role](Images/Average_Age_by_Department_and_Job_Role.png)

**Managers are the most senior employees** across all departments, averaging 47–50 years. In contrast, **Research Scientists (avg. ~34)** and **Laboratory Technicians (~34)** are among the youngest cohorts — which may partly explain higher attrition in those roles. Sales Representatives are the youngest at around **30 years old**.

---

### 7. 💰 Average Monthly Income by Role & Department

![Average Monthly Income](Images/Average_Monthly_Income.png)

Compensation follows a steep hierarchy:

| Tier | Roles | Avg. Monthly Income |
|------|-------|---------------------|
| 🥇 Top | HR Manager | ₹18,089 |
| 🥈 Senior | R&D Manager, Sales Manager, Research Director | ₹16,034 – ₹17,130 |
| 🥉 Mid | Healthcare Rep, Manufacturing Director | ₹7,295 – ₹7,529 |
| 📉 Entry | Lab Technician, Research Scientist, Sales Rep | ₹2,626 – ₹3,240 |

The **5x income gap** between entry-level and managerial roles is a critical attrition risk factor — particularly for young Research Scientists and Lab Technicians who make up the largest talent pool.

---

### 8. 🏢 Career Mobility — Total Companies Worked For

![Total Companies Worked For](Images/Total_Companies_worked_for.png)

Most employees have worked at **1–2 companies** before IBM, suggesting relatively stable career histories. The sharp drop-off after company #2 holds for both genders. However, employees with experience at **6–9 companies** still exist in meaningful numbers — these serial job-changers may warrant targeted retention strategies.

---

## 📌 Key KPIs at a Glance

<div align="center">

| Metric | Value |
|--------|-------|
| 👥 Total Employees | **1,470** |
| 📅 Avg. Years at Company | **7.008** |
| 🔧 Avg. Total Working Years | **11.28** |
| 🎂 Average Age | **36.92** |
| ♀️ Female Workforce | **40%** |
| ♂️ Male Workforce | **60%** |
| 🎓 Top Education Field | **Life Sciences (606)** |
| 💼 Largest Job Role | **Sales Executive (326)** |

</div>

---

## 💡 Key Business Insights

```
🔴  RISK IDENTIFIED   →  Entry-level roles (Lab Technicians, Research Scientists) are
                         young, numerous, and underpaid — the highest attrition risk combo.

🟡  WATCH CLOSELY     →  Single employees form a large segment (470+) and have fewer
                         personal anchors, correlating with higher voluntary turnover.

🟢  STRENGTH NOTED    →  Life Sciences & Medical backgrounds form a deep talent pipeline.
                         Investing in their development can reduce external hiring costs.

🔵  GENDER GAP        →  40/60 female-to-male split, widest in technical and sales roles.
                         Targeted hiring initiatives could improve representation.
```

---

## 🛠️ Tools & Technologies

| Tool | Role in Project |
|------|-----------------|
| **Tableau Desktop** | Dashboard design, interactive filters, and all visualizations |
| **Microsoft Excel** | Data cleaning, formatting, and preprocessing |
| **IBM HR Dataset** | 1,470 employee records across 35 variables |

---

## 🧠 Skills Demonstrated

`Data Cleaning` · `Exploratory Data Analysis` · `HR Analytics` · `People Analytics`  
`Tableau Dashboard Development` · `KPI Design` · `Business Intelligence`  
`Interactive Data Visualization` · `Workforce Analytics` · `Storytelling with Data`

---

## 📁 Repository Structure

```
IBM-HR-Analytics-Dashboard/
│
├── 📊 Dashboard/
│   └── IBM HR analytics dashboard.twbx       ← Open in Tableau Desktop
│
├── 📂 Dataset/
│   └── HR-Employee-Attrition.xlsx            ← Raw IBM HR data
│
├── 🖼️ Images/
│   ├── IBM_Dashboard.png
│   ├── Gender_in_the_Company.png
│   ├── Gender_and_Marital_Status.png
│   ├── Job_Role_and_Gender.png
│   ├── Total_Employees_by_Education_Field.png
│   ├── Total_employees_by_Job_role_and_Department.png
│   ├── Average_Age_by_Department_and_Job_Role.png
│   ├── Average_Monthly_Income.png
│   └── Total_Companies_worked_for.png
│
└── 📄 README.md
```

---

## 🚀 How to Use

```bash
# Step 1: Clone the repository
git clone https://github.com/nidhishkamboj/IBM-HR-ANALYTICS-DASHBOARD.git

# Step 2: Open the dashboard
# → Launch Tableau Desktop or Tableau Public
# → Open: Dashboard/IBM HR analytics dashboard.twbx

# Step 3: Explore
# → Use department/role filters to drill down
# → Hover on any chart for detailed tooltips
# → KPI tiles update dynamically with your selections
```

---

## 👤 About the Author

<div align="center">

**Nidhish Kamboj**  
*Data Analyst | Business Intelligence | HR Analytics*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nidhishkamboj)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nidhishkamboj)

</div>

---

<div align="center">

*If this project helped you or sparked ideas, drop a ⭐ — it means a lot!*

**© 2025 Nidhish Kamboj**

</div>

