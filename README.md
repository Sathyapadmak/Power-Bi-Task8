
# 📊 Student Performance Analysis Dashboard

**An interactive data visualization project built using Microsoft Power BI to explore student academic performance through KPI cards, charts, tables, and filters.**

---

## 📌 Project Overview

The **Student Performance Analysis Dashboard** is a data visualization project developed using **Microsoft Power BI**. It presents student academic performance through interactive visualizations, KPI cards, tables, and filters across **two report pages**.

The dashboard helps users explore subject-wise scores and overall student results in a clear and organized format.

---

## 🎯 Project Objectives

- 📚 Analyze student performance across subjects.
- ➗ Compare average scores in **Mathematics, Reading, and Writing**.
- 🍩 Understand the distribution of overall student results (Pass vs Fail).
- 🎛️ Explore student performance using interactive filters.
- 👥 Compare performance across race/ethnicity groups, gender, lunch type and test preparation course.
- 📊 Present academic data through clear and meaningful visualizations.

---

## 🛠️ Tools and Technologies

| Icon | Tool | Purpose |
|:----:|------|---------|
| 📊 | **Microsoft Power BI Desktop** | Dashboard development and visualization |
| 🔄 | **Power Query** | Data preparation and transformation, if used |
| 🧮 | **DAX** | Calculations and measures (averages, pass %, pass students, etc.) |
| 🔗 | **Data Modeling** | Dim Student and Fact Scores tables |
| 📁 | **Student Performance Dataset** | Source data for the analysis |

---

## 📈 Dashboard Features

### 📄 Page 1: Overview

#### 📊 Key Performance Indicators (KPIs)

| Icon | KPI | Value |
|:----:|-----|:-----:|
| ✍️ | **Avg Writing Score** | 68.05 |
| 📖 | **Avg Reading Score** | 69.17 |
| ➗ | **Avg Math Score** | 66.09 |
| 🏆 | **Overall Pass %** | 0.95 (94.9%) |
| 🎓 | **Pass Students** | 949 |
| 🎖️ | **Distinction Child** | 198 |

#### 📉 Visualizations

| Icon | Visual | Description |
|:----:|--------|-------------|
| 📊 | **Average of Score** | Column chart comparing average scores across math, reading and writing |
| 🍩 | **Student ID: Pass vs Fail** | Donut chart: 949 Pass (94.9%) and 51 Fail (5.1%) |

---

### 📄 Page 2: Detailed Analysis

#### 📊 Visualizations

| Icon | Visual | Description |
|:----:|--------|-------------|
| 🔢 | **KPI Cards** | Avg Writing, Reading and Math score |
| 📊 | **Clustered Column Chart** | Avg Math, Reading and Writing score by test preparation course |
| 🧮 | **Matrix by Race/Ethnicity** | Avg Math, Reading, Writing and Overall Average for groups A to E |
| 📋 | **Detail Table** | Gender, race/ethnicity, lunch and test preparation course with average subject scores |

---

### 🎛️ Interactive Filters

Slicers are available on both pages:

| Icon | Slicer |
|:----:|--------|
| 🎓 | Grade |
| 🚻 | Gender |
| 📚 | Subject |
| 👥 | Race/Ethnicity |
| 📝 | Test Preparation Course |
| 🍱 | Lunch |

These filters allow users to explore the available data based on selected categories.

---

## 🖼️ Dashboard Screenshots

### 📄 Page 1: Overview

<img width="1916" height="1021" alt="Screenshot 2026-11-26 100530" src="https://github.com/user-attachments/assets/c9701b5e-77e6-4223-8772-dcca48f210d3" />


### 📄 Page 2: Detailed Analysis

<img width="1917" height="1016" alt="Screenshot 2026-11-26 100637" src="https://github.com/user-attachments/assets/41a309db-ef1f-41e3-8b53-306e062f8bc5" />

---

## 📌 Key Insights

Based on the dashboard with **no filters applied**:

| Metric | Value |
|--------|:-----:|
| ✍️ Avg Writing Score | **68.05** |
| 📖 Avg Reading Score | **69.17** |
| ➗ Avg Math Score | **66.09** |
| 📈 Overall Average | **67.77** |
| ✅ Pass | **949** students (94.9%) |
| ❌ Fail | **51** students (5.1%) |
| 🎖️ Distinction | **198** students |

### 👥 Overall Average by Race/Ethnicity

| Group | Avg Math | Avg Reading | Avg Writing | Overall Average |
|:-----:|:--------:|:-----------:|:-----------:|:---------------:|
| Group A | 61.63 | 64.67 | 62.67 | 62.99 |
| Group B | 63.45 | 67.35 | 65.60 | 65.47 |
| Group C | 64.46 | 69.10 | 67.83 | 67.13 |
| Group D | 67.36 | 70.03 | 70.15 | 69.18 |
| Group E | 73.82 | 73.03 | 71.41 | 72.75 |

> 💡 Reading has the highest overall average and Math the lowest. Among race/ethnicity groups, **Group E** has the highest overall average (72.75) and **Group A** the lowest (62.99).

---

## 🔍 Analysis Opportunities

The dashboard can be used to explore:

- 📚 Differences in average scores across subjects.
- 🍩 The distribution of students by overall result.
- 👥 Performance patterns across gender and race/ethnicity groups.
- 🍱 Differences based on lunch type.
- 📝 Potential patterns associated with test preparation courses.
- 🎛️ Changes in displayed results when applying subject and demographic filters.

> ⚠️ **Note:** Specific findings should be reported only after checking the dashboard results.

---

## 💡 Learning Outcomes

Through this project, the following skills can be demonstrated:

- 📊 Creating interactive multi-page reports in Power BI.
- 🔢 Presenting key metrics using KPI cards.
- 📈 Choosing appropriate visualizations for data analysis.
- 🎛️ Using slicers to filter and explore data.
- 🧮 Writing DAX measures for averages and pass percentages.
- 🧩 Organizing dashboard layouts for readability.
- 💬 Communicating information through data visualization.

---

## 📁 Project Structure

```
📦 student-dashboard
 ┣ 📂 images
 ┃ ┣ 🖼️ dashboard-page1.png
 ┃ ┗ 🖼️ dashboard-page2.png
 ┣ 📊 student dashboard.pbix
 ┣ 📄 StudentsPerformance.csv
 ┗ 📘 README.md
```

> File names `.pbix` and `.csv` are examples. Replace them with your actual file names.

---

## 📝 Conclusion

The **Student Performance Analysis Dashboard** demonstrates how Microsoft Power BI can be used to present and explore student academic data through interactive KPI cards, charts, tables, and filters.

The project provides a clear way to compare subject-wise average scores, examine the distribution of overall student results, and drill into performance by race/ethnicity, gender, lunch type and test preparation course.

---
