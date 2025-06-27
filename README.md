# HR-Analytics-Predicting-Employee-Attrition
A project that analyzes employee attrition patterns using the IBM HR dataset. The project includes data preprocessing, EDA, model building (Logistic Regression), SHAP value analysis, a Power BI dashboard, and PDF reports with insights and prevention suggestions.


## 📌 Overview
This project aims to identify the key reasons behind employee attrition and predict future resignations using machine learning models. It also provides actionable insights for HR teams using Power BI dashboards and SHAP explainability.

---

## 📂 Project Files

- `HR Analytics.ipynb` – Jupyter notebook with code for EDA, preprocessing, and modeling
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` – IBM HR analytics dataset
- `Attrition_Prevention_Suggestions.pdf` – Final PDF with HR recommendations
- `Employee_Attrition_Project_Report.pdf` – Summary report of project workflow and findings
- `HR Analytics - Predict Employee Attrition.pbix` – Power BI dashboard file

---

## 🛠️ Tools Used

- **Python** (Jupyter Notebook)
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Scikit-learn**
- **Power BI** for dashboards
- **SHAP** for explainable AI

---

## 🔍 Project Workflow

1. **Data Collection**  
   Dataset sourced from IBM HR Analytics Attrition data.

2. **Data Cleaning & Preprocessing**  
   - Encoded categorical features  
   - Created grouped fields like AgeGroup and IncomeGroup

3. **Exploratory Data Analysis (EDA)**  
   - Visualized attrition trends by department, job role, age, income, etc.

4. **Model Building**  
   - Trained Logistic Regression model  
   - Evaluated with accuracy, precision, recall, F1-score

5. **Model Interpretation with SHAP**  
   - Identified most influential features for attrition

6. **Visualization**  
   - Interactive Power BI dashboard built from processed CSV

7. **Reporting**  
   - Confusion matrix plotted and exported  
   - Two PDFs: project summary + prevention strategies

---

## ✅ Key Insights

- OverTime and low Job Satisfaction are top drivers of attrition.
- Sales and Human Resources departments show higher attrition rates.
- Low income and long commute distances correlate with higher resignation risk.

---

## 📈 Output Samples

| Report | Description |
|--------|-------------|
| `Employee_Attrition_Project_Report.pdf` | Abstract, tools, steps, and conclusion |
| `Attrition_Prevention_Suggestions.pdf` | Actionable HR recommendations based on data |

---

