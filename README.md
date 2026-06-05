# AIML Internship - Week 1 Assignment

# Student Performance Analysis

## Internship Week Summary

This repository contains the Week 1 AIML Internship assignment focused on:

- Dataset Analysis
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation
- GitHub Documentation and Reporting

---

## Author

**Kashish Patel**  
B.Sc. Information Technology  
AIML Internship Program

---

## Project Objective

The objective of this project is to analyze student academic performance data, identify meaningful patterns, perform data cleaning, generate visual insights, and create business-oriented recommendations based on data-driven findings.

---

## Dataset Information

### Dataset Name

Students Performance in Exams

### Dataset Source

https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

### Dataset Description

The dataset contains demographic and academic information of students, including:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

An additional feature called **AverageScore** was created during the analysis to represent overall academic performance.

---

## Libraries Used

The following Python libraries were used:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- IPykernel

---

## Tasks Performed

### Task 1: Student Performance Dataset Analysis

Performed:

- Dataset loading and inspection
- Dataset preview using head() and tail()
- Shape analysis
- Data type verification
- Missing value analysis
- Duplicate record analysis
- Feature understanding
- Data cleaning
- Target variable creation
- Descriptive statistics generation
- Observation writing
- Dataset summary preparation

### Task 2: Data Visualization Project

Created visualizations including:

- Histogram of Average Scores
- Test Preparation vs Average Score Boxplot
- Reading Score vs Writing Score Scatter Plot
- Correlation Heatmap
- Parental Education vs Average Score Bar Chart

Each visualization includes interpretation and insights.

### Task 3: Business Insight Report

Prepared a business-oriented report containing:

- Objective
- Dataset Summary
- Analysis Approach
- Business Questions
- Key Findings
- Recommendations
- Limitations
- Conclusion

---

## Key Findings

### 1. Test Preparation Matters

Students who completed the test preparation course achieved significantly higher average scores than students who did not complete the course.

### 2. Reading and Writing Are Strongly Related

Reading and writing scores demonstrated a very strong positive correlation, indicating a close relationship between the two academic skills.

### 3. Most Students Show Moderate Performance

The majority of students scored between 60 and 80 marks across subjects.

### 4. Academic Scores Are Highly Correlated

Performance in one subject is strongly associated with performance in other subjects.

### 5. Parental Education Influences Performance

Students whose parents have higher education levels tend to achieve slightly higher average scores.

---

## Repository Structure

```text
AIML_Week1_Assignment/
│
├── data/
│   ├── raw/
│   │   └── StudentsPerformance.csv
│   │
│   └── cleaned/
│       └── students_performance_cleaned.csv
│
├── notebooks/
│   ├── week1_analysis.ipynb
│   └── week1_business_report.ipynb
│
├── outputs/
│   ├── charts/
│   └── reports/
│
├── screenshots/
│
├── src/
│
├── README.md
│
└── requirements.txt
```

---

## Visualizations Generated

- Distribution of Average Scores
- Test Preparation Impact Analysis
- Reading vs Writing Relationship
- Correlation Heatmap
- Parental Education Analysis

---

## Screenshots

### Dataset Preview

![Dataset Preview](screenshots/Dataset%20Preview.png)

### Missing Value Analysis

![Missing Values](screenshots/Missing%20Value%20Analysis.png)

### Descriptive Statistics

![Descriptive Statistics](screenshots/Descriptive%20Statistics.png)

### Distribution Plot

![Distribution Plot](screenshots/Histogram.png)

### Correlation Heatmap

![Heatmap](screenshots/HeatMap.png)

### Business Report Preview

![Business Report](screenshots/Business%20Report.png)

---

## How to Run

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3. Open Jupyter Notebook or VS Code

Run:

```text
notebooks/week1_analysis.ipynb
```

and

```text
notebooks/week1_business_report.ipynb
```

---

## Results

The analysis demonstrates that:

- Test preparation positively impacts academic performance.
- Reading and writing skills are strongly connected.
- Academic scores show strong positive correlations.
- Demographic and educational factors influence student outcomes.
- Data-driven analysis can help identify opportunities for educational improvement.

---

## Conclusion

This project successfully applied data cleaning, exploratory data analysis, visualization, and business reporting techniques to a real-world educational dataset.

The findings provide meaningful insights into factors associated with student academic performance and demonstrate the practical application of data analysis techniques in educational decision-making.

---

## Internship Program

WeIntern Pvt Ltd – AIML Internship Program

Week 1 Assignment Submission
