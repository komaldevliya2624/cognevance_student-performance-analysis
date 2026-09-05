# 📊 Student Performance Analysis

## 📌 Project Overview

This project analyzes the academic performance of **5,000 students** using Python and data analysis techniques.

The objective of this project is to explore student performance, identify important academic patterns, analyze relationships between different factors, and generate meaningful insights from the dataset.

The analysis covers academic scores, attendance, study hours, previous-year performance, gender, parental education, internet access, extracurricular activities, performance levels, and pass/fail status.

---

## 🎯 Objectives

* Analyze overall student academic performance.
* Calculate important performance KPIs.
* Analyze subject-wise performance.
* Study the relationship between attendance and final percentage.
* Analyze study hours and academic performance.
* Compare performance across gender groups.
* Analyze previous-year performance.
* Examine parental education and internet access.
* Analyze extracurricular activity participation.
* Perform correlation analysis.
* Categorize students into performance levels.
* Generate actionable insights and recommendations.

---

## 📂 Project Structure

```text
Student Performance Project/
│
├── Dataset/
│   └── student_performance.csv
│
├── Notebook/
│   └── student_performance_analysis.ipynb
│
├── Visualization/
│   ├── studyhours_vs_finalpercentage.png
│   ├── attendance_vs_finalpercentage.png
│   ├── subject_performance.png
│   ├── performance_level.png
│   └── ...
│
├── report/
│   └── project_report.pdf
│
└── README.md
```

> File names may differ depending on the final files uploaded to the repository.

---

## 📊 Dataset

The dataset contains information about **5,000 students**.

The analysis includes variables related to:

* Academic scores
* Final percentage
* Attendance
* Study hours per day
* Previous year score
* Gender
* Parental education
* Internet access
* Extracurricular activities
* Performance level
* Pass/Fail status

---

## 🧹 Data Cleaning & Preprocessing

The dataset was prepared for analysis using **Pandas**.

The preprocessing included:

* Loading the dataset.
* Exploring rows and columns.
* Checking data types.
* Checking missing values.
* Handling data-quality issues where required.
* Converting variables into appropriate data types.
* Preparing categorical variables for analysis.
* Checking the final dataset before analysis.

---

## ⚙️ Feature Engineering

Additional features were created to make the analysis more meaningful.

### Performance Level

Students were categorized into:

* **Excellent**
* **Good**
* **Average**
* **Poor**

### Pass/Fail Status

Students were classified according to their final academic result to calculate the overall pass rate.

---

## 📈 Key Performance Indicators

| KPI                      |              Value |
| ------------------------ | -----------------: |
| Total Students           |          **5,000** |
| Average Final Percentage |         **67.48%** |
| Average Attendance       |         **74.92%** |
| Average Study Hours      | **3.29 hours/day** |
| Overall Pass Rate        |         **94.70%** |

---

## 📚 Subject Performance

The subject-wise analysis showed:

* 🥇 **English** has the highest average subject score.
* 📉 **Science** has the lowest average subject score.

This analysis helps identify stronger and weaker academic areas.

---

## 📊 Performance Level Distribution

| Performance Level |  Students |
| ----------------- | --------: |
| Good              | **2,191** |
| Average           | **1,951** |
| Excellent         |   **593** |
| Poor              |   **265** |

The **Good** performance category contains the largest number of students.

---

## 📌 Correlation Analysis

Correlation analysis was performed to understand the linear relationship between selected variables and Final Percentage.

| Variable            | Correlation with Final Percentage |
| ------------------- | --------------------------------: |
| English Score       |                         **0.592** |
| Attendance          |                         **0.001** |
| Previous Year Score |                        **-0.017** |

### Key Insight

**English Score** has the strongest reported relationship with Final Percentage among these variables, with a correlation of **0.592**.

Attendance and Previous Year Score show very weak relationships with Final Percentage in this dataset.

> Correlation indicates association and does not prove causation.

---

## 🔍 Key Findings

* The dataset contains **5,000 students**.
* Average Final Percentage is **67.48%**.
* Average Attendance is **74.92%**.
* Average Study Hours are **3.29 hours/day**.
* Overall Pass Rate is **94.70%**.
* English has the highest average subject score.
* Science has the lowest average subject score.
* English Score has the strongest reported correlation with Final Percentage (**0.592**).
* Attendance has a very weak correlation with Final Percentage (**0.001**).
* Previous Year Score has a very weak negative correlation with Final Percentage (**-0.017**).
* Most students fall into the **Good** and **Average** performance categories.

---

## 💡 Recommendations

Based on the analysis:

1. Provide additional academic support in weaker subjects such as Science.
2. Continue strengthening English performance.
3. Identify students in the Average and Poor categories for additional academic support.
4. Use multiple factors when evaluating student performance instead of relying on a single variable.
5. Use data analysis regularly to monitor academic performance and identify areas requiring attention.
6. Interpret correlation results carefully and avoid treating correlation as causation.

---

## 🛠️ Technologies & Tools

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **GitHub**

---

## 📊 Visualizations

The project includes visualizations for different aspects of student performance, including:

* attendencepercentage_vs_finalpercentage
* averagefinalpercentage_vs_attendencegroup
* averagefinalscore_by_gender
* averagescore_by_subject
* pass_vs_failstudents
* performancelevel_by_students
* studyhours_vs_averagefinalpercentage
* studyhours_vs_finalpercentages
* many other charts and graphs

## 📄 Project Report

The complete project report is available here:

📁 **`report/project_report.pdf`**

The report contains the complete methodology, analysis, findings, recommendations, and conclusion.

---

## 🧠 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Statistical Analysis
* Correlation Analysis
* Data Visualization
* KPI Development
* Business/Analytical Insights
* Python Data Analysis
* Pandas
* Matplotlib

---

## 🏁 Conclusion

This project demonstrates how Python-based data analysis can be used to understand student performance and identify meaningful patterns within educational data.

The analysis provides an overview of academic performance, subject-level strengths and weaknesses, performance categories, and relationships between selected variables and final percentage.

Overall, the project demonstrates an end-to-end data analysis workflow, from **data cleaning and preprocessing to visualization, analysis, insights, and reporting**.

---

## 👩‍💻 Author

**Komal Devliya**

BCA | Aspiring Data Analyst

**Skills:** Python • Pandas • Excel • Matplotlib • Data Analysis
