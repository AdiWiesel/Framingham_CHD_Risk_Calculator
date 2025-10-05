# 💓 Framingham 10-Year CHD Risk Calculator (Excel Project)

This project is an interactive **Excel dashboard** that estimates a person’s 10-year risk of developing **coronary heart disease (CHD)** using the **Framingham 2008 general CVD risk model (BMI-based equation)**.  

It was designed as both an **educational tool** and a **portfolio project** to demonstrate skills in **data cleaning, formulas, PivotTables, conditional formatting, and dashboard design**.

---

## 📌 Project Description
- Accepts user inputs (age, sex, smoking status, diabetes, blood pressure, cholesterol, BMI, treatment status).  
- Returns a **10-year CHD risk %**, a **color-coded risk category**, and a **dynamic plain-English interpretation**.  
- Supports comparisons to observed outcomes from the Framingham cohort dataset.  

---

## ⭐ Features
- **User Input Form**: Intuitive input fields with dropdowns and validation.  
- **Result Card**: Risk percentage, risk category (Low/Moderate/High), and number of risk factors.  
- **Dynamic Interpretation Line**: Plain-English explanation that updates automatically.  
- **Cohort-Based Charts**:  
  - CHD Risk by Age Group  
  - CHD Risk by Smoking Status  
- **Insights Box**: Key takeaways from Framingham study and risk factor importance.  

---

## 🛠 How to Use
1. Open the Excel file.  
2. Go to the **CALCULATOR** sheet.  
3. Enter your details in the **blue User Inputs form**.  
4. The **Result Card** updates instantly with:  
   - Final 10-year CHD risk %  
   - Risk category (color-coded)  
   - Number of risk factors  
5. Review the **charts and insights** to understand your profile in context.  

---

## 📊 Interpretation of Results
- **Low Risk (<10%)** → Favorable profile, lifestyle maintenance recommended.  
- **Moderate Risk (10–20%)** → Elevated risk, lifestyle and medical follow-up may be needed.  
- **High Risk (>20%)** → Strongly elevated risk, clinical evaluation recommended.  

⚠️ *Note: This calculator is for educational and research purposes only, not for clinical diagnosis or treatment.*

---

## 📑 Technical Notes
- Based on **D’Agostino et al., Circulation 2008** (Framingham BMI-based risk model).  
- Implemented entirely in **Microsoft Excel**:  
  - Formulas (logarithmic risk model implementation)  
  - PivotTables & PivotCharts  
  - Conditional Formatting  
  - Dashboard-style layout  
- Includes a **logistic regression feature importance chart** for interpretability.  

---

## 👤 Credits
- **Created by:** Adi Wiesel  
- **Date:** October 2025  

---
