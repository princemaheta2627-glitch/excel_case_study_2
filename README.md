# 📊 Advanced Excel Data Analysis Case Study

![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Advanced-217346?logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-blue)
![Dashboard](https://img.shields.io/badge/Dashboard-Excel-success)
![Business Analytics](https://img.shields.io/badge/Business-Analytics-orange)

---

# 📌 Project Overview

This project demonstrates advanced data analysis techniques using **Microsoft Excel** through two practical business case studies.

The first case study focuses on **student performance analysis**, where nested logical functions, conditional aggregation, ranking, and reporting techniques are applied. The second case study analyzes **NSE Nifty 50 financial market data**, showcasing lookup automation, trend visualization, and interactive reporting.

The project illustrates how Excel can be used as a powerful analytical tool before transitioning to technologies such as Python, SQL, Power BI, and Tableau.

---

# 🎯 Project Objectives

- Perform rule-based data classification
- Apply advanced Excel formulas and functions
- Build interactive lookup systems
- Analyze grouped data using aggregation functions
- Rank performance using statistical calculations
- Visualize trends using professional charts
- Present business insights through dashboards

---

# 📂 Project Structure

```text
Excel-Case-Study-2/
│
├── Excel_Case_Study_2.xlsx
├── Excel_Case_Study_Project_Report.pdf
├── README.md
│
├── Images/
│   ├── Student_Analysis.png
│   ├── State_Summary.png
│   ├── Lookup_Table.png
│   ├── Trend_Chart.png
│   └── Dashboard.png
```

---

# 🛠️ Tools & Technologies

- Microsoft Excel
- Excel Tables
- Data Validation
- Charts
- Conditional Formatting
- Formula-Based Analysis

---

# 📊 Excel Functions Used

- IF()
- Nested IF()
- VLOOKUP()
- COUNTIF()
- SUMIF()
- AVERAGEIF()
- SUM()
- AVERAGE()
- RANK()
- CONCATENATE()

---

# 📁 Case Study 1 — Student Performance Analysis

## 📌 Business Scenario

Analyze examination results of students from different states by assigning grades, generating summaries, and ranking state performance.

---

## 📊 Tasks Performed

- Grade Classification
- Student Result Generation
- State-wise Summary
- Ranking States
- Average Marks Calculation
- Total Marks Calculation

---

## 📈 Grade Classification

| Marks | Grade |
|--------|-------|
| < 35 | FAIL |
| 35 – 49 | PASS |
| 50 – 59 | Second Class |
| 60 – 74 | First Class |
| ≥ 75 | Distinction |

---

## 🧮 Sample Formula

```excel
=IF(E13<35,"FAIL",
IF(E13<50,"PASS",
IF(E13<60,"2nd Class",
IF(E13<75,"1st CLASS","DISTINCTION"))))
```

---

## 📊 Functions Used

- Nested IF
- COUNTIF
- SUMIF
- AVERAGEIF
- RANK
- CONCATENATE

---

## 🔍 Key Insights

- Delhi achieved the highest average marks.
- Orissa ranked second in overall performance.
- Gujarat showed moderate but inconsistent results.
- Bihar recorded the lowest average marks.
- State ranking identified clear performance differences among regions.

---

# 📈 Case Study 2 — NSE Nifty 50 Trend Analysis

## 📌 Business Scenario

Analyze historical **NSE Nifty 50** market data by creating an interactive lookup system and financial trend visualizations.

---

## 📊 Dataset

The dataset contains daily:

- Open Price
- High Price
- Low Price
- Close Price
- Shares Traded
- Turnover

(March 2021 – June 2021)

---

## 🔎 Interactive Lookup

Created a dynamic lookup tool using **VLOOKUP** that retrieves market information based on the selected trading date.

### Sample Formula

```excel
=VLOOKUP(R9,A6:G88,2,FALSE)
```

Returns the Open Price.

---

## 📊 Charts Created

- Close Price Trend
- Turnover Analysis
- Combination Chart (Close Price vs Turnover)

---

## 🔍 Key Insights

- Nifty experienced a sharp decline during March before recovering steadily.
- High trading turnover generally coincided with significant price movements.
- Interactive lookup simplifies retrieval of daily market information.
- Combination charts provide a clear relationship between trading volume and market movement.

---

# 📈 Skills Demonstrated

### Data Preparation

- Data Cleaning
- Structured Tables
- Data Validation

### Data Analysis

- Conditional Logic
- Lookup Functions
- Aggregation
- Ranking
- Statistical Analysis

### Visualization

- Column Charts
- Combination Charts
- Dashboard Design

### Reporting

- Business Insights
- Executive Summary
- Analytical Reporting

---

# 📚 Excel Concepts Covered

- Nested Logical Functions
- Lookup Tables
- Conditional Aggregation
- Ranking Analysis
- Dynamic Lookup Systems
- Financial Data Analysis
- Trend Visualization
- Interactive Reporting

---

# 💼 Business Applications

This project demonstrates Excel applications in:

- Education Analytics
- Academic Reporting
- Financial Market Analysis
- Business Intelligence
- Dashboard Reporting
- Decision Support Systems

---

# 🚀 Future Improvements

- Replace VLOOKUP with XLOOKUP
- Add Pivot Tables and Pivot Charts
- Build Interactive Excel Dashboard
- Automate reporting with Power Query
- Connect to Power BI
- Add Slicers and Timelines
- Develop KPI Dashboard

---

# 📸 Screenshots

Store project screenshots inside the **Images** folder.

```text
Images/
│
├── Student_Analysis.png
├── State_Summary.png
├── Lookup_Table.png
├── Trend_Chart.png
└── Dashboard.png
```

---

# ▶️ Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/excel-case-study-2.git
```

Open the workbook in **Microsoft Excel** and explore the formulas, charts, and interactive lookup features.

---

# 🎯 Learning Outcomes

By completing this project, you will gain practical experience with:

- Advanced Excel formulas
- Business rule implementation
- Lookup automation
- Data aggregation
- Dashboard creation
- Financial data analysis
- Data visualization
- Analytical thinking

---

# 👨‍💻 Author

**Prince Maheta**

📊 Aspiring Data Analyst | Excel | Power BI | Python

🔗 **GitHub:** https://github.com/princemaheta2627-glitch

🔗 **LinkedIn:** https://linkedin.com/in/your-linkedin-profile

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📄 License

This project is created for learning, educational, and portfolio purposes.
