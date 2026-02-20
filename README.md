🎓 **Abeda Inamdar CS Department – Result Analysis Dashboard**  
An interactive **Power BI Result Analytics Dashboard** built to analyze **FY, SY, and TY (B.Sc. Computer Science)** results from the college’s **official result PDFs**.  
This project demonstrates the complete **Data Analyst workflow**—from **manual data extraction → error handling → cleaning → modeling → dashboarding**—to convert raw result sheets into clear, decision-ready insights.

---

## 📌 Project Overview  
The **CS Department Result Analysis Dashboard** helps understand:

✔ Overall **student performance** (Pass/Fail, Average SGPA)  
✔ **Class-wise comparison** (FY vs SY vs TY)  
✔ **Grade distribution** and result trends  
✔ **Subject-wise performance** (average marks / top subjects)  
✔ **Gender-wise performance**  
✔ **Top 10 students** ranking by Percentage/SGPA  
✔ Interactive filtering using **slicers** (Class, Grade, Gender, Result)

Instead of checking result PDFs and Excel manually, this dashboard provides a **fast and visual performance analysis tool**.

---

## 🎯 Objective  
The goal of this project is to:

1) Convert official **result PDF data into structured Excel datasets** (FY/SY/TY)  
2) Practice **real-world data quality challenges** by intentionally adding errors  
3) Collaboratively **detect, fix, and validate** those errors  
4) Build a clean, analysis-ready dataset for reporting  
5) Create interactive **Power BI dashboards** for insights and comparisons

---

## 🛠️ Tech Stack Used  
📊 **Power BI Desktop** – Dashboard development & visualization  
📂 **Power Query** – Data cleaning, formatting, transformations  
🧠 **DAX (Data Analysis Expressions)** – Measures/KPIs (Pass%, Avg SGPA, counts, rankings)  
📁 **Microsoft Excel** – Manual data entry + structured sheets for FY/SY/TY  
🧩 **Data Modeling** – Master table, relationships, filters/slicers  
🖼 **PNG Export** – Dashboard screenshots for documentation

---

## 📂 Data Source  
The dataset was prepared from **official result PDFs** of the **Computer Science Department** (Abeda Inamdar Senior College of Arts, Science and Commerce, Pune).

The Excel dataset contains fields such as:

1) Student details (Name, Seat No, Enrollment No, Class)  
2) Gender  
3) Subjects & Marks  
4) Total Marks & Percentage  
5) Grade  
6) SGPA  
7) Result (PASS/FAIL)

> Note: Data was manually entered from PDFs into Excel, then cleaned and validated before using in Power BI.

---

## 🧹 Data Preparation & Cleaning Workflow  
✔ Manual data entry from FY/SY/TY PDFs into Excel  
✔ Intentionally inserted common errors (typos, wrong totals, incorrect grades, missing values)  
✔ Cross-checked each other’s entries and corrected errors  
✔ Standardized values (Grade, Result, Subject naming)  
✔ Ensured numeric consistency (Marks, Percentage, SGPA)  
✔ Final merged structure for cross-class comparison in Power BI

---

## 📊 Dashboard Features & Insights  

### 🔢 Key Performance Indicators (KPIs)  
Shows a quick snapshot like:  
- **Total Students**  
- **Pass Students / Fail Students**  
- **Average SGPA**

(These KPIs update dynamically based on selected class/filters.)

---

### ✅ Pass vs Fail Analysis  
Pie/summary visuals showing pass and fail distribution.  
➡ Helps quickly understand overall performance and failure rate.

---

### 🏅 Grade Distribution  
Class-wise grade distribution (A++, A, B, C, D, etc.).  
➡ Helps identify performance concentration and academic outcomes.

---

### 📚 Subject-wise Performance  
- Average marks by subject  
- Top subjects (high scoring) and weak subjects (low scoring)  
➡ Helps identify which subjects need more focus and improvement.

---

### 👥 Gender-wise Performance  
Performance comparison across **Male vs Female** (based on dashboard measure).  
➡ Supports performance breakdown and category analysis.

---

### 🥇 Top 10 Students  
Dynamic table showing top performers with:  
- Name  
- Percentage  
- SGPA  
➡ Highlights rankers and overall toppers.

---

### 🆚 FY vs SY vs TY Comparison (Final Dashboard)  
A combined dashboard to compare:  
- KPIs across FY/SY/TY  
- Grade and result trends  
- Performance patterns by class  
➡ Helps department-level comparison at a glance.

---

## 💡 Insights Derived (Examples)  
✔ Identify which class has higher pass percentage (FY vs SY vs TY)  
✔ Detect subject-wise difficulty areas through low average marks  
✔ Observe grade distribution differences among classes  
✔ Track performance differences by gender (as per dataset)  
✔ Identify consistent top-performing students

---

## 📷 Dashboard Preview  
Add screenshots in your repo and link like this:

```md
![FY Dashboard](images/fy_dashboard.png)
![SY Dashboard](images/sy_dashboard.png)
![TY Dashboard](images/ty_dashboard.png)
![Final Comparison Dashboard](images/final_comparison_dashboard.png)
```

---

## ▶️ How to Use  
1) Download/Clone this repository  
2) Open the **.pbix** file in **Power BI Desktop**  
3) Use slicers (Class, Grade, Gender, Result) to explore insights  
4) View individual class pages (FY/SY/TY) + final comparison page

---

## 👨‍💻 Contributors  
- **Mubeen Shaikh**  
- **Simran Sayyed**  
- **Azmin Kazi**

---

## 📌 Disclaimer  
This project is created for **educational and academic analysis purposes**. Data is based on official result PDFs and was manually entered/cleaned for learning and dashboard practice.

---

Agar tum mujhe **repo ka actual project name** (new repo name) bata do, main isi README ke top title/one-line description ko bilkul GitHub “About” section ke hisaab se short karke de dunga + proper **folder structure** (pbix / data / images) bhi suggest kar dunga.
