# 📊 Forest Cover Type Classification

This project predicts the forest cover type based on cartographic and environmental features.  
It applies **Machine Learning models** such as **Random Forest** and **XGBoost**.

---

## 🚀 Project Workflow
1. **Data Exploration & Cleaning**  
   - Checked data types, missing values, and unique values.  
   - Handled one-hot and continuous features separately.  

2. **Feature Preparation**  
   - Encoded one-hot variables (`Wilderness Area`, `Soil Type`).  

3. **Model Training**  
   - **Random Forest** (baseline model).  
   - **XGBoost** (tuned hyperparameters).  

4. **Evaluation Metrics**  
   - Precision, Recall, and F1-Score.  
   - Cross-validation for consistency.  
   - Compared models accuracy scores through a bar plot.  

---

## 📈 Results
| Model           | Precision | Recall | F1-score | Cross-val Mean |
|-----------------|-----------|--------|----------|----------------|
| Random Forest   | ~0.95     | ~0.95  | ~0.95    |  ————          |
| XGBoost (tuned) | ~0.97     | ~0.97  | ~0.97    | ~0.97          |

- Random Forest: ✅ Helped identify Feature Importance and served as a strong baseline with consistent performance.
- XGBoost(with hypertunning): ⭐ Best performance with higher F1-Score and precision.  

**Final Choice:** XGBoost performed best for this dataset.

---

## 📦 Dataset
- CoverType (UCI)

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib
- Seaborn
- scikit-learn  
- Xgboost

---

## 📂 Project Structure
forest-cover-type-classification/

│── data/

│     └── covtype.data       # Original dataset

│

│── notebooks/

│     └── forest_classification.ipynb  # Jupyter Notebook with full workflow

│

│── README.md                           # Project documentation

│── requirements.txt                    # Python dependencies

│── .gitignore                          # Ignore unnecessary files

│── LICENSE                             # License file
