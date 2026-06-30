<div align="center">

# 📊 ABC Company Employee Data Analysis

<p>
A Python-based Exploratory Data Analysis (EDA) project on the ABC Company Employee Dataset.
</p>

<p>
<img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas">
<img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy">
<img src="https://img.shields.io/badge/Matplotlib-Visualization-orange">
<img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0">
<img src="https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab">
</p>

</div>

---

## 📌 Project Overview

This project analyzes the **ABC Company Employee Dataset**, consisting of **458 employee records**. The objective is to preprocess the dataset, perform exploratory data analysis (EDA), create visualizations, and derive meaningful insights into the company's workforce.

---

## 📂 Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset | ABC Company Employee Dataset |
| Total Records | **458** |
| Total Columns | **9** |

**Dataset Features**

- Name
- Team
- Number
- Position
- Age
- Height
- Weight
- College
- Salary

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- ✔️ Checked for missing values in the dataset.
- ✔️ Replaced the **Height** column with randomly generated values between **150 cm and 180 cm**.
- ✔️ Created a separate dataset for salary-based analysis by removing rows with missing salary values.
- ✔️ Ensured data consistency before performing analysis.

---

## 📈 Analysis Tasks

The following analyses were performed on the dataset:

### 1️⃣ Employee Distribution Across Teams
- Calculated the number of employees in each team.
- Computed the percentage distribution of employees across teams.

### 2️⃣ Employee Distribution by Position
- Segregated employees based on their positions.
- Counted employees in each position.

### 3️⃣ Predominant Age Group
- Grouped employees into age ranges.
- Identified the predominant age group.

### 4️⃣ Salary Expenditure Analysis
- Calculated total salary expenditure for each team.
- Calculated total salary expenditure for each position.
- Identified the team and position with the highest salary expenditure.

### 5️⃣ Correlation Between Age and Salary
- Calculated the Pearson correlation coefficient.
- Visualized the relationship using a scatter plot with a regression line.

---

## 📊 Visualizations

The project includes visualizations for:

- 📌 Employee Distribution Across Teams
- 📌 Employee Distribution by Position
- 📌 Age Group Distribution
- 📌 Salary Expenditure by Team
- 📌 Salary Expenditure by Position
- 📌 Correlation Between Age and Salary

---

## 💡 Key Insights

- Employees are distributed across multiple teams with no single team dominating the workforce.
- The majority of employees belong to the **19–25** age group, indicating a relatively young workforce.
- The **Center (C)** position has the highest total salary expenditure.
- Salary expenditure varies across different teams and positions.
- The correlation coefficient between **Age** and **Salary** is approximately **0.214**, indicating a **weak positive correlation**.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation and Analysis |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Google Colab | Development Environment |

---

## 📁 Repository Structure

```text
ABC-Employee-Data-Analysis/
│
├── ABC_Employee_Analysis.ipynb
├── ABC_Employee.csv
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone <repository-url>
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook using **Google Colab** or **Jupyter Notebook**.

4. Run all cells sequentially to reproduce the analysis and visualizations.

---

## 📜 Conclusion

This project demonstrates the application of **Python-based data preprocessing, exploratory data analysis, and visualization techniques** to extract meaningful insights from employee data. The analysis provides an understanding of workforce distribution, salary expenditure patterns, employee demographics, and the relationship between age and salary.
