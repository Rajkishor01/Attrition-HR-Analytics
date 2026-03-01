# Attrition-HR-Analytics
# 📊 HR Analytics Dashboard — Power BI

> An interactive Power BI dashboard designed to analyze employee attrition trends, helping HR teams make data-driven decisions to improve employee retention.

---

## 📁 File

| File | Description |
|------|-------------|
| `HR_Analytics.pbix` | Power BI report file |

---

## 🎯 Objective

To identify key factors driving employee attrition across departments, job roles, age groups, gender, education, and overtime status — enabling HR professionals to take proactive retention actions.

---

## 📄 Dashboard Pages

### Page 1 — Overview
High-level KPI summary of the workforce.

| KPI Card | Description |
|----------|-------------|
| 👥 Total Employee | Total number of employees in the organization |
| ❌ Total Attrition | Total number of employees who left |
| 📉 Attrition Rate | Percentage of employees who left |
| 📅 Avg. Years at Company | Average tenure of all employees |

Also includes:
- **Area Chart** — Attrition trend over time
- **Slicers** — Interactive filters for Job Role and other dimensions

---

### Page 2 — Attrition by Demographics
Breakdown of attrition across various groups.

| Visual | Insight |
|--------|---------|
| 🏢 Attrition by Department | Which departments lose the most employees |
| 👔 Attrition by Job Role | Which roles have the highest attrition |
| 👩‍💼👨‍💼 Attrition by Age Group | Age segments most affected by attrition |
| 🚺🚹 Attrition by Gender | Gender-based attrition comparison |

---

### Page 3 — Attrition Deep Dive
Deeper analysis into specific behavioral and career factors.

| Visual | Insight |
|--------|---------|
| 🔢 Attrition by Age | Exact age-wise attrition line chart |
| 🎓 Attrition by Education Field | Impact of educational background on attrition |
| 🕒 Attrition by Over Time | Whether overtime work leads to higher attrition |

---

## 🗂️ Dataset Fields Used

| Field | Type | Description |
|-------|------|-------------|
| `Age` | Numeric | Employee age |
| `Age Group` | Category | Grouped age brackets |
| `Attrition` | Binary | Yes / No — whether employee left |
| `Attrition Count` | Measure | Count of employees who left |
| `Attrition %` | Measure | Attrition rate (%) |
| `Average Years At Company` | Measure | Mean tenure |
| `Department` | Category | HR, Sales, R&D, etc. |
| `Education Field` | Category | Field of study |
| `Gender` | Category | Male / Female |
| `Job Role` | Category | Role designation |
| `Over Time` | Binary | Yes / No |
| `Total Employee` | Measure | Total headcount |
| `Work Life Balance` | Rating | Scale rating |
| `Years At Company` | Numeric | Tenure in years |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development (Version 2024.11) |
| **DAX** | Custom measures (Attrition Rate, Attrition Count, etc.) |
| **Power Query** | Data transformation and cleaning |

---

## 📊 Dashboard Structure

```
HR_Analytics.pbix
│
├── Page 1 — Overview
│     ├── KPI Cards (Total Employee, Attrition Count, Attrition Rate, Avg Years)
│     ├── Area Chart (Attrition Trend)
│     └── Slicers (Job Role filter)
│
├── Page 2 — Demographics
│     ├── Column Chart — By Department
│     ├── Column Chart — By Job Role
│     ├── Column Chart — By Age Group
│     └── Bar Chart   — By Gender
│
└── Page 3 — Deep Dive
      ├── Line Chart  — By Age
      ├── Bar Chart   — By Education Field
      └── Bar Chart   — By Over Time
```

---

## 🚀 How to Use

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Open the `HR_Analytics.pbix` file
3. Use the **slicers** on Page 1 to filter by Job Role
4. Navigate across pages using the bottom tabs
5. Click on any chart element to **cross-filter** other visuals on the same page

---

## 💡 Key Insights You Can Discover

- Which **department** has the highest attrition rate?
- Does **overtime** significantly increase the chance of an employee leaving?
- What **age group** is most likely to leave?
- Is there a **gender gap** in attrition?
- How does **education field** relate to job retention?

---

## 📌 Use Cases

- **HR Managers** — Monitor workforce health and identify at-risk groups
- **Data Analysts** — Practice building KPI dashboards with DAX measures
- **Business Leaders** — Make strategic decisions to improve employee retention



---

## 📜 License

This project is intended for educational and portfolio purposes.
