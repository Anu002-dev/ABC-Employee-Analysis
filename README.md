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
<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter">
</p>

</div>

---

## 📌 Project Overview

This project analyzes the **ABC Company Employee Dataset** consisting of **458 employee records**. The objective is to preprocess the dataset, perform exploratory data analysis, visualize key findings, and derive meaningful insights about the company's workforce.

---

## 📂 Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset | ABC Company Employee Dataset |
| Total Records | **458** |
| Total Columns | **9** |

**Features**

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

The following preprocessing steps were performed before analysis:

- ✔️ Checked for missing values.
- ✔️ Replaced the **Height** column with randomly generated values between **150 cm and 180 cm**.
- ✔️ Created a separate dataset for salary-based analysis by removing rows with missing salary values.
- ✔️ Ensured data consistency throughout the analysis.

---

## 📈 Analysis Performed

The following analyses were carried out:

### 1️⃣ Employee Distribution Across Teams
- Calculated employee count for each team.
- Computed percentage distribution.

### 2️⃣ Employee Distribution by Position
- Segregated employees based on their positions.
- Counted employees in each position.

### 3️⃣ Predominant Age Group
- Grouped employees into different age ranges.
- Identified the most represented age group.

### 4️⃣ Salary Expenditure Analysis
- Determined total salary expenditure by team.
- Determined total salary expenditure by position.

### 5️⃣ Age vs Salary Correlation
- Calculated the Pearson correlation coefficient.
- Visualized the relationship using a scatter plot.

---

## 📊 Visualizations

The project includes graphical representations for:

- 📌 Team-wise Employee Distribution
- 📌 Position-wise Employee Distribution
- 📌 Age Group Distribution
- 📌 Salary Expenditure by Team
- 📌 Salary Expenditure by Position
- 📌 Correlation between Age and Salary

---

## 💡 Key Insights

- Employees are distributed across multiple teams with no single team dominating the workforce.
- The majority of employees belong to the **19–25** age group, indicating a relatively young workforce.
- Salary expenditure varies across teams and positions.
- The **Center (C)** position has the highest total salary expenditure.
- The correlation coefficient between **Age** and **Salary** is approximately **0.214**, indicating a **weak positive correlation**.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Development Environment |

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

## 🚀 How to Run

1. Clone this repository.

```bash
git clone <repository-url>
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells.

---

## 📜 Conclusion

This project demonstrates the use of **Python for data preprocessing, exploratory data analysis, and visualization** to gain meaningful insights from employee data. The analysis highlights workforce distribution, salary expenditure patterns, age demographics, and the relationship between age and salary.

---

<div align="center">

**Developed using ❤️ with Python**

</div>
