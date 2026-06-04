# 👥 HR Analytics Dashboard — Power BI

A 3-page Power BI dashboard analyzing employee attrition, workforce composition, and retention risk across departments and job roles. Built on the IBM HR Attrition dataset with a star schema data model and role-based security.

---

## 📸 Screenshots

| Attrition & Workforce | Workforce Analysis |
|---|---|
| ![Attrition](employee_attrition_and_workforce_insights_.png) | ![Workforce](Workforce_Analysis.png) |

| Retention & Risk | |
|---|---|
| ![Retention](retention_and_risk_insights.png) | |

---

## 🗂️ Dashboard Pages

| Page | Purpose | Key Visuals |
|---|---|---|
| **Employee Attrition & Workforce Insights** | Top-level attrition KPIs | 5 KPI cards, IBM logo, bar chart, 2 donut charts, column chart, advanced slicer |
| **Workforce Analysis** | Demographics and satisfaction | Bar, donut, column, scatter charts, 4 slicers, insights textbox |
| **Retention & Risk Insights** | Department risk identification | Pivot table with conditional formatting, multi-row card, bar/column/line charts, 4 slicers |

---

## ✅ Key Features

- **Star Schema Model** — DimDepartment, DimEducationField, DimGender, DimJobRole + Fact table
- **Row Level Security (RLS)** — Department-level access for HR BPs, full view for HR leadership
- **Conditional Formatting** — Pivot table highlights high attrition roles in red/green instantly
- **Advanced Slicer Visual** — Modern Power BI slicer for intuitive filtering
- **6 Navigation Buttons** — Seamless cross-page navigation
- **Multi-row Card** — Compact department-wise attrition summary

---

## 🧮 DAX Measures

| Measure | Description |
|---|---|
| `Total Employees` | Total headcount |
| `Attrition Count` | Number of employees who left |
| `Attrition Rate %` | DIVIDE(Attrition Count, Total Employees) |
| `Overtime Attrition %` | Attrition rate among overtime employees |
| `Average Salary` | Average monthly income |
| `Avg Years at Company` | Average employee tenure |
| `Average Age` | Average employee age |

---

## 📐 Data Model

- **Type:** Star schema
- **Fact table:** WA_Fn-UseC-HR-Em... (main HR dataset)
- **Dimensions:** DimDepartment, DimEducationField, DimGender, DimJobRole
- **Dataset:** IBM HR Employee Attrition (public dataset)

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Report building and visualization |
| DAX | Attrition and workforce measures |
| Power Query | Star schema creation and transformation |
| Excel | Source dataset |

---

## 📥 How to Use

1. Download `hr_analytics.pbix` from this repo
2. Open in **Power BI Desktop** (free from Microsoft)
3. Navigate pages using the arrow buttons
4. Use slicers to filter by Department, Gender, Job Role, Age Group
5. Page 3 pivot table shows attrition risk with red/green conditional formatting
6. View `hr_analytics.pdf` for a static walkthrough

---

## 👤 Author
k.kadheerakushi
[LinkedIn Profile URL]:www.linkedin.com/in/kamanur-kadheera-kushi-87a7652b7
[GitHub Profile URL]:https://github.com/kamanurkushi/
