# Attrition Analysis

## 📌 Project Overview

This project focuses on **Employee Attrition Analysis** using data analytics techniques. Attrition, or employee turnover, is a critical challenge faced by organizations, and analyzing patterns in workforce data can help in understanding the factors leading to attrition and aid in developing better employee retention strategies.

The notebook demonstrates data exploration, visualization, preprocessing, and insights extraction to identify key drivers of employee attrition.

---

## 📂 Project Structure

```
├── Attrition Analysis_DA.ipynb   # Jupyter Notebook with full analysis
├── README.md                     # Project documentation
├── dataset/                      # Folder containing dataset
│   └── employee_attrition.csv    # Employee Attrition dataset

```

---

## 📊 Dataset

* **Type:** Employee Attrition dataset (tabular format)
* **Features include:**

  * Demographics (Age, Gender, Education, Marital Status)
  * Job-related (JobRole, Department, YearsAtCompany, JobSatisfaction, WorkLifeBalance)
  * Compensation (MonthlyIncome, SalaryHike)
  * Performance (OverTime, PerformanceRating)
* **Target Variable:** `Attrition` (Yes/No)

---

## 🔎 Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Normalization/standardization

2. **Exploratory Data Analysis (EDA)**

   * Univariate and bivariate analysis
   * Correlation heatmap
   * Visualizations (histograms, bar plots, pie charts, box plots)

3. **Insights**

   * Identifying patterns in employee attrition
   * Factors strongly correlated with attrition

---

## 📈 Results & Findings

* Employees with **long working hours (OverTime)** are more likely to leave.
* **Low job satisfaction and poor work-life balance** increase attrition rates.
* Certain job roles/departments experience higher turnover compared to others.
* Younger employees with fewer years at the company show higher attrition.
---

## ⚙️ Technology Used

* **Python**
* **Jupyter Notebook**
* **Libraries:**

  * `pandas` – Data manipulation
  * `numpy` – Numerical operations
  * `matplotlib` & `seaborn` – Data visualization
  * `scikit-learn` – Preprocessing & ML utilities

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/attrition-analysis.git
   cd attrition-analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook:

   ```bash
   jupyter notebook Attrition Analysis_DA.ipynb
   ```

---

## 👤 Author

**Bishal Jaysawal**

* 📧 [https://www.linkedin.com/in/bishal-7bj/]
* 💻 Passionate about **Data Analysis | Machine Learning | Cybersecurity**
