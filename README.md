# 🏥 Insurance Charges Analysis & Prediction

This project explores and analyzes health insurance data to understand the factors influencing **medical insurance charges**. It includes detailed **data analysis, visualization, and statistical testing** using Python.

---

## 📊 Project Overview

The goal of this project is to:
- Analyze how features like **age, gender, BMI, smoking habits, and region** affect insurance charges.  
- Perform **data visualization** to identify key patterns and outliers.  
- Use **statistical tests (Pearson correlation and Chi-Square test)** to determine relationships between variables.  
- Build insights that support accurate **charge prediction** and feature selection.

---

## 🧩 Steps Performed

1. **Data Cleaning**  
   - Handled missing and inconsistent values.  
   - Created new categorical features (e.g., `bmi_category`, `is_smoker`, `is_female`).  

2. **Exploratory Data Analysis (EDA)**  
   - **Boxplots** for comparing distributions across categorical features.  
   - **Line Graphs** for visualizing trends and relationships.  
   - **Histograms** for understanding the distribution of charges and BMI.  
   - **Heatmaps** for correlation between numerical variables.

3. **Statistical Tests**  
   - **Pearson Correlation:** Checked correlation strength between continuous variables.  
   - **Chi-Square Test:** Determined association between categorical variables and insurance charges.

4. **Feature Selection**  
   - Retained significant variables based on p-values (< 0.05).  
   - Features like `is_smoker`, `region_southeast`, `is_female`, and `bmi_category_Obese` were found significant.

---

## 🧠 Key Insights
- **Smoking** has the strongest effect on insurance charges.  
- **Obesity** and **gender** also show notable influence.  
- Regional differences exist but are less significant.  
- Non-significant features were dropped to simplify the model.

---

## 🛠️ Libraries and Frameworks Used

- **Python**  
- **Pandas**, **NumPy** – Data handling  
- **Matplotlib**, **Seaborn** – Visualization  
- **SciPy**, **Statsmodels** – Statistical analysis

## 🧑‍💻 Author

-**Ishaan Rana**
-**Data Analyst | Python | SQL | Power BI**
📍 **New Delhi, India**
