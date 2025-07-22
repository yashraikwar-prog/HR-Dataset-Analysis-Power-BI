# HR Dataset Analysis & Visualization

This project presents a comprehensive analysis and visualization of an HR dataset using interactive dashboards. It helps uncover key insights related to employee demographics, attrition, satisfaction, salary trends, department performance, and recruitment effectiveness.

---

## 📊 Dashboard Overview

The interactive dashboard provides:

* **Total Employees**: 311
* **Current Employees**: 207
* **Attrition Rate**: 0.33
* **Departments Covered**: 6
* **Average Salary**: \~\$69,020
* **Average Age**: 45.98
* **Average Tenure**: 2.01 years

---

## 🔍 Key Insights

* **Attrition**:

  * Highest attrition in **Production** department.
  * **Single** employees show slightly higher attrition.
  * **Simon Roup** has the highest attrition among managers.

* **Employee Satisfaction**:

  * Majority satisfaction concentrated in **Production** (66.69%).
  * Highest dissatisfaction noted in **Sales**.

* **Recruitment Sources**:

  * **Indeed** is the most used recruitment platform, followed by **LinkedIn**.

* **Salary & Absences**:

  * **Executive** roles have the highest average salary.
  * **Production** has the highest number of absences.

---

## 📁 Dataset Description

| Column                                        | Description                           |
| --------------------------------------------- | ------------------------------------- |
| `Employee_Name`                               | Full name of the employee             |
| `EmpID`                                       | Employee ID                           |
| `MarriedID`, `MaritalStatusID`                | Marital identifiers                   |
| `GenderID`                                    | Gender identifier                     |
| `EmpStatusID`                                 | Employment status (Active/Terminated) |
| `DeptID`                                      | Department ID                         |
| `PerfScoreID`                                 | Performance score ID                  |
| `FromDiversityJobFairID`                      | Diversity hiring indicator            |
| `Salary`                                      | Annual salary                         |
| `Termd`                                       | 1 if terminated, 0 otherwise          |
| `Position`, `Department`, `ManagerName`, etc. | Self-explanatory HR attributes        |
| `EngagementSurvey`, `EmpSatisfaction`         | Survey scores from employees          |
| `Absences`                                    | Number of days absent                 |
| `DateofHire`, `DateofTermination`, `DOB`      | Key HR dates                          |

---

## 🛠️ Tools Used

* **Power BI** for data visualization
* **Excel/CSV** as the data source
* **DAX** and **Power Query** for data transformation

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/hr-dashboard.git
   ```
2. Open the Power BI file (`.pbix`) to interact with the dashboard.
3. Filter by **Year**, **Manager**, **Sex**, or **Department** to explore deeper insights.

---
