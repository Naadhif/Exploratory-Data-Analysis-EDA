# Student Performance Exploratory Data Analysis (EDA)

This repository contains a Python-based Exploratory Data Analysis (EDA) project focused on analyzing student performance using a synthetic dataset. The script demonstrates foundational data science workflows, including data generation, structure inspection, attribute classification, and descriptive statistical analysis.

---

## 🚀 Features

- **Synthetic Dataset Generation:** Automatically generates a realistic dataset of 100 students containing academic and behavioral features.
- **Data Inspection:** Inspects dataset dimensions, column names, and data types.
- **Attribute Classification:** Categorizes features into appropriate data types:
  - *Identifier*
  - *Categorical* (Nominal, Ordinal, Binary)
  - *Numerical* (Discrete, Continuous)
- **Descriptive Statistics:** 
  - Computes statistical summaries (mean, standard deviation, min/max, quartiles) for numerical features.
  - Calculates frequency distributions and percentages for categorical features.

---

## 📊 Dataset Attributes

The generated dataset (`student_performance_data.csv`) includes the following columns:
- `Student_ID`: Unique identifier for each student.
- `Major`: The student's academic major.
- `Attendance_Category`: Categorical rating of attendance (e.g., High, Medium, Low).
- `Status`: Academic status (e.g., Active, Graduated, Dropout).
- `Study_Hours_Per_Week`: Number of hours spent studying weekly (Discrete).
- `Attendance_Percentage`: Precise attendance rate (Continuous).
- `Midterm_Score`: Score obtained in the midterm exam.
- `GPA`: Cumulative Grade Point Average (Continuous).

---

## 🛠️ Prerequisites & Installation

To run this script, ensure you have Python installed along with the required data science libraries:

```bash
pip install pandas numpy
```

---

## 💻 Usage

Clone the repository and run the script to generate the dataset and view the EDA results in your terminal:

```bash
python student_eda.py
```

---

## 📈 Example Output

The script outputs clean console summaries, such as:
1. **Dataset Info:** Non-null counts and memory usage.
2. **Numerical Summaries:** Central tendencies and spreads for variables like GPA and study hours.
3. **Categorical Distributions:** Proportions of students across different majors and attendance tiers.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check issues page or submit a pull request.
