# 🧠 Quality Quest: Comparative Study of ML Algorithms for Prediction

This project compares multiple Machine Learning algorithms on the **Wine Quality dataset** from the UCI Machine Learning Repository.  
The goal is to identify the most accurate and efficient model for predicting wine quality based on physicochemical tests.

## 📊 Dataset
- **Source:** [UCI ML Repository – Wine Quality Dataset]([https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/](https://archive.ics.uci.edu/dataset/186/wine+quality))
- **Attributes:** 11 numerical input features + 1 target label (`quality`).

## ⚙️ Algorithms Compared
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  
- Support Vector Classifier  

## 🧪 Evaluation Metrics
Each model is compared using:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

## 🚀 Tools & Libraries
- Python, Pandas, NumPy, Matplotlib, Seaborn  
- scikit-learn  

## 📈 Results Summary
| Model | Accuracy | F1 Score | Notes |
|--------|-----------|----------|-------|
| Random Forest | 0.87 | 0.86 | Best performing |
| SVC | 0.84 | 0.82 | Balanced generalization |
| Decision Tree | 0.79 | 0.78 | Overfits slightly |

*(You’ll update this with your actual metrics later.)*

## 💻 Run on Google Colab
You can open and run this notebook directly here:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ajmalalikhan07/Quality-Quest-ML-Comparison/blob/main/Quality_Quest.ipynb)

## 🧩 Future Enhancements
- Build a **Streamlit app** to visualize model comparison interactively.  
- Extend to **regression-based datasets** for broader applicability.  

---

👨‍💻 **Author:** [Ajmal Ali Khan](https://www.linkedin.com/in/ajmal-ali-khan-a09471222/)  
📬 *ajmalalikhan1203@gmail.com*
