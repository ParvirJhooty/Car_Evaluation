# 🚗 Car Evaluation Classification

## 📌 Project Overview
This project analyzes the **Car Evaluation Dataset** from the UCI Machine Learning Repository to predict the **acceptability of cars** (unacceptable, acceptable, good, very good) based on six categorical attributes:

- Buying price  
- Maintenance cost  
- Number of doors  
- Passenger capacity  
- Luggage size  
- Safety rating  

The goal is to compare multiple machine learning algorithms and determine which model provides the highest predictive accuracy.

---

## ⚙️ Methods
We implemented and evaluated the following classification algorithms:

- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- **Support Vector Machine (SVM)**

Each model was tested **with and without feature selection** to assess its impact on performance. Data preprocessing involved encoding categorical attributes as numerical values for model compatibility.

---

## 📊 Results
| Algorithm         | Accuracy | Weighted F1-Score |
|-------------------|-----------|-------------------|
| Decision Tree      | 88%        | 0.87 |
| Random Forest      | **98%**    | **0.98** |
| KNN                | 95%        | 0.95 |
| Naive Bayes        | 76%        | 0.76 |
| SVM                | 92%        | 0.91 |

- **Random Forest performed the best**, achieving 98% accuracy and the highest precision, recall, and F1-scores.  
- Feature selection had **no significant impact**, suggesting all attributes are useful predictors.  
- **Safety rating** was identified as the most important feature.

---

## 📁 Repository Contents
- `Car_Crash_Evaluation.ipynb` — Jupyter Notebook with data preprocessing, model training, and evaluation code.
- `CPS 844 Report.pdf` — Final report summarizing methodology, analysis, and results.

---
