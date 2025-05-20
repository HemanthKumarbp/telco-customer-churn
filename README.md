
# 📊 Telco Customer Churn Analytics Project

This project explores customer churn in a telecommunications company using Python for data cleaning and Power BI for dashboard visualization. The goal is to identify key factors driving churn and provide actionable insights for business decision-makers.

---

## 🧩 Project Overview

- **Domain:** Telecommunications
- **Objective:** Analyze customer churn behavior to help the business retain customers and reduce churn rate
- **Tech Stack:**
  - 📌 **Python (Pandas, NumPy, Matplotlib)** – for data cleaning & preprocessing
  - 📌 **Power BI** – for interactive dashboard and visual analysis

---

## 🧼 Step 1: Data Cleaning in Python

Performed the following tasks using Python:

- Removed duplicates and missing values
- Converted data types (e.g., TotalCharges from object to float)
- Created new columns like:
  - `TenureGroup` (binned tenure)
  - `TotalServices` (sum of services subscribed)
  - `AvgChargesPerMonth` (monthly cost average)

Saved the cleaned data as `cleaned_telco_data.csv` for Power BI import.

---

## 📈 Step 2: Dashboard in Power BI

Used **Power BI** to build a visually interactive dashboard from the cleaned dataset.

### ✅ Key Visuals:

1. **Churn by Gender** (Clustered Bar Chart)
2. **Churn by Tenure Group** (Column Chart)
3. **Churn by Contract Type** (Stacked Column)
4. **Churn vs Total Services** (Column Chart)
5. **Average Monthly Charges by Churn** (Boxplot or Clustered Bar)
6. **Slicers for Filtering**:
   - Gender
   - Internet Service
   - Contract
   - Payment Method
   - Tenure Group

---

## 🎨 Design Highlights

- Consistent color scheme:
  - 🔴 Red = Churned customers (`Yes`)
  - 🟢 Green = Active customers (`No`)
- Slicers for user-driven exploration
- Clear titles and tooltips for all visuals
- Clean layout with soft backgrounds and borders

---

## 📊 Business Insights

- Month-to-month and fiber optic customers show higher churn
- Customers with shorter tenure and high monthly charges are more likely to churn
- Total number of subscribed services has a strong correlation with churn behavior

---

## 📁 File Structure

```
📁 Telco_Customer_Churn_Project
├── cleaned_telco_data.csv
├── churn_dashboard.pbix
├── README.md
└── python_data_cleaning_script.ipynb
```

---

## ✅ Future Improvements

- Build a churn prediction model using classification (Logistic Regression, XGBoost)
- Deploy dashboard via Power BI Service or integrate with Microsoft Teams

---

## 🧠 Credits

- Dataset: Kaggle: Telco Customer Churn Dataset
- Original dataset source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- Tools used: Python, Power BI Desktop

---

## 📬 Contact

Feel free to reach out if you have any questions or suggestions:
- 📧 Email: hemanthkumarbp19@gmail.com
- 🌐 Portfolio: https://www.linkedin.com/in/hemanth-kumar-bp/
     
