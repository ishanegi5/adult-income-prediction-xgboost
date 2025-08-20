# Adult Income Prediction using XGBoost

This project predicts whether an individual's income exceeds $50K/year based on demographic and employment attributes. The dataset is the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult).

## 📊 Dataset
- Source: UCI Machine Learning Repository  
- Features: 14 (age, education, occupation, marital status, hours-per-week, etc.)  
- Target: Income (`<=50K` or `>50K`)  

## 🛠️ Tech Stack
- Python
- Pandas, NumPy (data processing)
- Scikit-learn (preprocessing, evaluation metrics)
- XGBoost (model training)
- Matplotlib/Seaborn (visualization)

## ⚙️ Steps
1. Load dataset (`adult.data`, `adult.test`)
2. Clean missing values (`?` entries)
3. Encode categorical features
4. Train-test split
5. Train **XGBoostClassifier**
6. Evaluate with accuracy, confusion matrix, and classification report

## 📈 Results
- **Accuracy:** ~96%
- **Confusion Matrix:**  
[[41, 2],
[ 2, 69]]

- **Classification Report:**
| Class | Precision | Recall | F1-score |
|-------|-----------|--------|----------|
| <=50K | 0.95      | 0.95   | 0.95     |
| >50K  | 0.97      | 0.97   | 0.97     |

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/ishanegi5/adult-income-prediction-xgboost.git
cd adult-income-prediction-xgboost

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook Adult_Income_XGBoost.ipynb

📌 Requirements
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn

📢 License

This project is open-source and available under the MIT License.

Author:
Isha Negi
