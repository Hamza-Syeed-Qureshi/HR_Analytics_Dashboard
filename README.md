# 📊 **HR Analytics Dashboard – Power BI**
A complete and interactive **HR Analytics Dashboard** developed in **Power BI**, designed to provide deep insights into employee attrition, workforce demographics, departmental distribution, salary analysis, and employee engagement patterns.  
This project showcases end-to-end data cleaning, modeling, visualization, and storytelling — ideal for HR teams, data analysts, and business decision-makers.

---

## 🧩 **Why HR Analytics?**
Employee attrition directly impacts business productivity, hiring costs, and organizational stability.  
This dashboard helps organizations:

- Identify **key drivers behind employee attrition**
- Evaluate how **salary, age, gender, and experience** affect retention
- Understand **departmental strengths and weaknesses**
- Improve **HR decision-making** through data-driven insights
- Plan **strategic interventions** to reduce turnover

---

## 📁 **Project Structure**
| File Name | Description |
|----------|-------------|
| **HR_Analytics.csv** | Raw dataset used for analysis and dashboard creation |
| **HR Analytics Dashboard.pdf** | Full PDF export of the Power BI dashboard |
| **README.md** | Detailed documentation of the project |

---

## 🧠 **Business Problems Addressed**
This dashboard answers critical HR questions:

- Which age groups have the highest attrition?
- Are certain job roles more vulnerable to turnover?
- Does monthly income impact attrition probability?
- Do males or females resign more?
- What is the distribution of employees across departments?
- Which education backgrounds contribute more to attrition?
- How do salary slabs impact employee retention?
- What is the overall attrition trend in the company?

---

## 🛠 **Tools & Technologies Used**
- **Power BI Desktop**
- **Power Query** for data cleaning
- **DAX** for measures and calculated columns
- **CSV file** as the main data source
- **Data Modeling (Star Schema approach)**

---

# 📊 **Dashboard Features & Visuals**

## 1️⃣ **Attrition Overview**
A high-level KPI card showing:
- Total Attrition Count  
- Attrition %  
- Total Employee Base  

Gives a quick snapshot of organizational health.

---

## 2️⃣ **Attrition by Monthly Income**
Visualizes whether employees with lower or higher incomes are more likely to leave.  
Helps identify if salary adjustments could reduce churn.

---

## 3️⃣ **Attrition by Education Field**
Shows attrition categorized by education background such as:
- Life Sciences  
- Medical  
- Marketing  
- Technical Degree  
- Human Resources  

Useful for targeted hiring strategies.

---

## 4️⃣ **Attrition by Age Group**
Breaks employees into:
- 18–25  
- 26–35  
- 36–45  
- 46–55  
- 56+  

Helps HR understand which age groups feel most dissatisfied.

---

## 5️⃣ **Attrition by Salary Slab**
Categorizes salary into slabs and visualizes churn.  
Helpful to determine whether compensation restructuring is required.

---

## 6️⃣ **Attrition by Job Role**
Displays attrition counts across roles like:
- Human Resources  
- Manager  
- Sales Executive  
- Research Scientist  
- Laboratory Technician  
- Healthcare Representative  

Critical for identifying job roles with high turnover.

---

## 7️⃣ **Department Employee Distribution**
Shows total number of employees in:
- HR  
- R&D  
- Sales  
Helps understand department size and workforce allocation.

---

## 8️⃣ **Gender-wise Attrition**
Shows whether men or women leave the company more frequently.  
Useful for gender diversity analysis.

---

# 🧱 **Data Modeling**
A well-structured **star schema** is used:
- **Fact Table** → Attrition & employee data  
- **Dimension Tables** → Education, Age, Gender, Job Role, Department, Salary  

Model ensures:
- Faster performance  
- Better filtering  
- Clean relationships  

---

# 🔍 **Data Cleaning Steps (Power Query)**
Performed transformations:
- Removed duplicates  
- Handled null values  
- Created age groups  
- Created salary slabs  
- Ensured correct data types  
- Standardized columns  

---

# 📐 **DAX Measures Used**
Examples:
- **Attrition Count**
- **Attrition Percentage**
- **Employee Count**
- **Monthly Income Bucketing**
- **Salary Slab Categorization**

These measures support interactive, dynamic visualizations.

---

# 🎯 **Key Insights from Dashboard**
- **Young employees (26–35)** show the highest attrition.
- **Lower salary groups** have a noticeably higher exit rate.
- Certain roles (like **Sales Executives** & **Laboratory Technicians**) show increased turnover.
- **Life Sciences & Medical fields** show higher attrition counts.
- Gender distribution indicates whether retention issues differ between men and women.
- Employees with fewer years at the company tend to leave more quickly.

---

# 👨‍💼 **Business Recommendations**
Based on insights:
- Provide **salary increments** for high-risk groups.
- Implement **career development plans** for vulnerable job roles.
- Improve **onboarding processes** for younger employees.
- Offer **flexible working policies** to reduce churn.
- Conduct **focused surveys** for departments with high attrition.

---

# 🚀 **How to Use This Project**
1. Download the repository  
2. Open the dashboard in **Power BI Desktop**  
3. Load the provided dataset (`HR_Analytics.csv`)  
4. Refresh the visuals  
5. Interact with filters to explore insights  

---

# 👤 **Author**
### **Hamza**  
Power BI | Data Analyst | Visualization Enthusiast  
If you found this interesting, feel free to ⭐ star the repository!

---

# ⭐ **Support & Contribution**
Contributions, issues, and feature requests are welcome!  
If you’d like new visuals, more insights, or advanced DAX, feel free to open an issue.

