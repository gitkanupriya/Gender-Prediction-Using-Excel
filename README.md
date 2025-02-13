# Gender Prediction Using Excel  

## 📌 Project Overview  
This project explores gender prediction using **Excel**, leveraging built-in functions like `IF()`, `RIGHT()`, `VLOOKUP()`, and **Pivot Tables**. By analyzing the **last letter of names**, we identify patterns and achieve an **81% accuracy** in predicting gender.  

---

## 📊 Dataset  
- **Total Records:** 2999  
- **Data Split:**  
  - 70% **Training Data**  
  - 30% **Validation Data** (Stratified Splitting)  

---

## 🛠 Methodology  
1. **Extract Last Letter** – Use `RIGHT()` to extract the last letter of names.  
2. **Analyze Frequency** – Identify how often each letter appears in male vs. female names.  
3. **Predict Gender**:  
   - If a letter is more common for a specific gender, classify accordingly.  
   - Use `VLOOKUP()` to find gender probabilities.  
   - Apply `IF()` to finalize gender predictions.  
4. **Validate Accuracy** – Evaluate predictions using **F1 Score** and a **Confusion Matrix**.  

---

## ⚡ Key Excel Functions Used  
| Function | Purpose |
|----------|---------|
| `RIGHT()` | Extracts the last letter of a name |
| `VLOOKUP()` | Finds the most probable gender based on training data |
| `IF()` | Compares probabilities and assigns gender |
| **Pivot Tables** | Summarizes data and detects gender trends |

---

## 📈 Results & Findings  
✔ **Accuracy:** 81%  
✔ **Key Insight:** Letters like **'A' & 'I'** are predominantly associated with **female** names.  

---

## 🎯 Conclusion  
This project demonstrates that **Excel alone** can be a powerful tool for **data analysis and gender prediction**, without requiring advanced programming!  

---

## 📝 How to Use  
1. **Open** `GenderPrediction.xlsx` in Excel.  
2. Navigate to the **Training Data** sheet.  
3. Check the **Pivot Table** for last-letter frequency analysis.  
4. **Enter a new name** in the **Test Data** section and let Excel predict the gender!  

---

🔹 **Author:** Kanupriya Nailwal  
📅 **Created Using:** Microsoft Excel  
🚀 **Technologies:** Data Analysis, Excel Functions, Pivot Tables  


