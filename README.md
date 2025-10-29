# 🌟 INX Future Inc. Employee Performance Analysis  

**Author:** Rijul Jamwal  
**Project Type:** IABAC Certified Data Scientist Project  
**Tools Used:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

---

## 🎯 Project Overview  
This project analyzes and predicts employee performance for **INX Future Inc.** using advanced data science techniques.  
The goal is to derive actionable HR insights — identifying top performance factors and predicting future performance trends.

---

## 🧩 Problem Statement  
INX Future Inc. aims to improve overall workforce productivity by understanding what drives employee performance.  
The company wants to:  
- Identify key factors that influence performance  
- Predict employee performance scores  
- Recommend HR strategies for improvement  

---

## 🧠 Machine Learning Approach  
- **Algorithm Used:** Random Forest Regressor  
- **Performance Metrics:** R² Score, MAE, RMSE  
- **Target Variable:** `PerformanceRating`  
- **Feature Engineering:** Label Encoding, Missing Value Treatment, Data Normalization  

---

## 🗂️ Project Structure  

INX_Future_Employee_Performance/
├── data/
│ ├── raw/ # Original dataset
│ ├── processed/ # Cleaned and processed data
│ │ ├── processed_data.csv
│ │ ├── feature_importance.csv
│ ├── external/
│
├── src/
│ ├── Data Processing/
│ │ ├── DataPreprocessing.ipynb
│ │ ├── DataExplorator.ipynb
│ ├── models/
│ │ ├── TrainModel.ipynb
│ │ ├── PredictModel.ipynb
│ ├── visualization/
│ │ ├── Visualize.ipynb
│
├── Project Summary/
│ ├── Requirement/
│ ├── Analysis/
│ │ ├── Analysis.ipynb
│ ├── Summary/
│ │ ├── summary.md
│
├── references/
│ ├── readme.txt
│ ├── data_dictionary.txt
│



---

## 📊 Key Insights  

1. Departments with better training programs show higher performance scores.  
2. Employee satisfaction level strongly correlates with performance.  
3. OverTime and DistanceFromHome show minimal influence on performance.  
4. Work-life balance and years with the current manager impact stability.  

---

## 💡 Recommendations  

- Introduce **quarterly satisfaction surveys** to track engagement.  
- **Expand training programs** for low-performing departments.  
- Use this predictive model for **HR talent screening and promotion decisions**.  

---

## 🧰 Technologies Used  

| Category | Tools |
|-----------|-------|
| Programming | Python 3.10 |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| IDE | Jupyter Notebook |
| Model | Random Forest Regressor |
| Data Format | Excel (.xlsx), CSV |

---

## 🧾 Results Summary  

| Metric | Value (approx.) |
|---------|----------------|
| **R² Score** | 0.688 |
| **MAE** | ~0.105 |
| **RMSE** | ~0.282 |

✅ The model shows **high predictive accuracy** and generalizes well across employee data.

---

📜 License

This project was developed as part of the IABAC Certified Data Scientist Program.
You are free to explore and learn from this code with proper credit.

🧑‍💻 Author

Rijul Jamwal
📧 rijuljamwal101@gmail.com

🎓 Certified Data Scientist (IABAC)
