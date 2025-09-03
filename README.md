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
| Model           | Precision | Recall | F1-score | Cross-val Mean | Accuracy |
|-----------------|-----------|--------|----------|----------------|----------|
| Random Forest   | ~0.95     | ~0.95  | ~0.95    |  ————          | 0.954    |
| XGBoost (tuned) | ~0.97     | ~0.97  | ~0.97    | ~0.97          | 0.973    |

- Random Forest: ✅ Helped identify Feature Importance and served as a strong baseline with consistent performance, but got stuck in 95% accuracy.
- XGBoost(with hypertunning): ⭐ Best performance with higher F1-Score, precision, and accuracy.  

**Final Choice:** XGBoost performed best for this dataset.

---

**✅ Business Impact**  
XGBoost provides highly accurate forest cover type predictions, **reducing classification errors** in ecological and forestry applications. This helps decision-makers **rely less on manual surveys** and make faster, data-driven environmental assessments.


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

│     └── covtype.zip       # Original dataset

│

│── notebooks/

│     └── forest_classification.ipynb  # Jupyter Notebook with full workflow

│

│── README.md                           # Project documentation

│── requirements.txt                    # Python dependencies

│── .gitignore                          # Ignore unnecessary files

│── LICENSE                             # License file
