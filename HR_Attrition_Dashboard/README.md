# HR Attrition Dashboard

This presents a detailed **HR Attrition Dashboard** built in Tableau to analyze workforce attrition patterns. The dashboard provides comprehensive insights into employee turnover across demographics, departments, job roles, and education levels, helping HR teams make data-driven decisions.

---

## Executive Summary

- **Attrition Rate**: **16.36%**
- **Total Attrition Count**: **243 employees**
- **Total Employees**: **1,485**

  <img width="1712" height="895" alt="Dashboard" src="https://github.com/user-attachments/assets/6bfa6f56-5e39-41d2-a02d-438c3ed2d197" />


The dashboard offers clear visibility into attrition contributors through filters and dynamic visual elements for better workforce planning and retention strategies.

---

## Key Visuals & KPIs

### 🔹 Departmental Attrition (Donut Charts)
- **Highest Headcount**: R&D (835)
- **Highest Attrition Count**:
  - R&D: 51
  - Sales: 92
  - HR: 12

### 🔹 Job Role Attrition (Horizontal Bar Chart)
- **Top Job Roles by Attrition**:
  - Sales Executive
  - Research Scientist
  - Laboratory Technician
- Managers and Directors show lower attrition comparatively.

### 🔹 Demographics

#### Gender-wise Attrition (Donut Charts)
- **Female Attrition**: 87 out of 592
- **Male Attrition**: 156 out of 893

#### Age Group (Bar Chart - Stacked)
- **Most Affected Age Group**: 27-35 (106 attritions out of 569)
- Younger (18–26) and middle-aged (36–44) also show notable turnover.

#### Education Field (Bar Chart - Stacked)
- **Top Fields with High Attrition**:
  - Life Sciences (89 attritions out of 613)
  - Medical (66 attritions out of 467)

---

## 📈 Attrition Trend (Time Series Line Chart)
- **Peak Attrition Periods**: Week 0 (73), Week 1 (71), Week 7 (31)
- Shows a sharp drop after Week 7 suggesting stabilization or onboarding adjustments.

---

## Survey Score Heatmap
Visual comparison of employee satisfaction across roles:
- **Lowest Scores**:
  - Human Resources
  - Laboratory Technicians
- **Better Survey Scores**: Managers, Research Directors

Color intensity reflects concentration of low scores — vital for intervention.

---

## Recent Attrition (Detail Cards)
Provides case-by-case attrition info with:
- Hourly Rate
- Job Satisfaction
- Salary Hike
- Monthly Income
- Performance Score
- Years at Company

> Example:
> - **Employee**: E_27  
>   **Role**: Sales Representative  
>   **Job Satisfaction**: 1  
>   **Salary Hike**: 23  
>   **Monthly Income**: $3,407

---

## Dashboard Contents

| Type        | Names                                                                 |
|-------------|-----------------------------------------------------------------------|
| **Dashboard**  | HR Attrition Dashboard                                               |
| **Story**      | Story (walkthrough or guided insights)                              |
| **Worksheets** | Age Group, Attrition Trend, Departments, Gender, Job Role, Survey Score, Education Field, Recent Attrition |
| **Datasource** | federated.1oo5vmk1djz13h18ebro5030pq0q                              |

---

## Key Insights

- **Job Roles** with high operational intensity (Sales, Lab Technicians) show high churn.
- **Age 27–35** group is most prone to attrition.
- **Survey Scores correlate** with attrition – especially in HR & Technical roles.
- **Salary Hike ≠ Retention**: Even high hikes didn’t retain some employees.
- **Medical & Life Sciences** fields suffer from high attrition — potential industry trend.

---

## Suggestions & Enhancements

- Include **exit interview sentiment analysis** (if available) to enrich insights.
- Add **interactive filters** for cross-drill between Job Role ↔ Age ↔ Satisfaction.
- Track **Attrition Cost Impact** on organization.
- Introduce **predictive attrition model** using historical trends.
- Implement **real-time alerts** for at-risk employees.

---

## How You Can Contribute

- Add HR metrics like **burnout risk**, **overwork indicators**, or **promotion stagnation**.
- Integrate with other systems (e.g., payroll, performance reviews).
- Apply **machine learning models** to predict next likely exits.

---
