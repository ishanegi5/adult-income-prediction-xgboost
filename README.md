# Breast Cancer Detection using XGBoost

This project uses the **Breast Cancer Wisconsin dataset** from `sklearn.datasets` to build a machine learning model that classifies tumors as **malignant** or **benign**.

## 📊 Dataset
- Source: `from sklearn.datasets import load_breast_cancer`
- Samples: 569
- Features: 30 numeric features (mean, standard error, and worst values of cell nuclei characteristics)
- Target:  
  - `0` → Malignant  
  - `1` → Benign  

## 🛠️ Tech Stack
- Python
- Pandas, NumPy (data handling)
- Scikit-learn (train/test split, metrics)
- XGBoost (model training)
- Matplotlib/Seaborn (optional visualizations)

## ⚙️ Steps
1. Load dataset with `load_breast_cancer()`
2. Train-test split
3. Train **XGBoostClassifier**
4. Evaluate with accuracy, confusion matrix, and classification report

## 📈 Results
- **Accuracy:** ~96%  
- **Confusion Matrix:**  
[[41, 2],
[ 2, 69]]

- **Classification Report:**
| Class | Precision | Recall | F1-score |
|-------|-----------|--------|----------|
| 0 (Malignant) | 0.95 | 0.95 | 0.95 |
| 1 (Benign)    | 0.97 | 0.97 | 0.97 |

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/ishanegi5/breast-cancer-detection-xgboost.git
cd breast-cancer-detection-xgboost

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook Breast_Cancer_XGBoost.ipynb

📌 Requirements
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn

📢 License

This project is open-source and available under the MIT License.

🔗 Author: Isha Negi
