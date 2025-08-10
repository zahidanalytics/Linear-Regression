# Linear-Regression
Predict house prices using Linear Regression on the Kaggle dataset. Includes data cleaning, feature engineering, log transformation, and RMSE evaluation. Generates Kaggle-ready submission files for leaderboard entry.

---

## 🧠 Concepts Covered
- **Linear Regression Theory** – equation, coefficients, bias
- **Data Cleaning & Exploration** – handling missing values, feature inspection
- **Feature Engineering** – log transformation, scaling
- **Model Evaluation** – RMSE on log-transformed target
- **Kaggle Submission Format** – `Id, SalePrice`

---

## 🛠️ Tech Stack
- **Python 3**
- **Google Colab**
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn

---

## 📊 Methodology
1. **Load Data** – `train.csv` and `test.csv` from Kaggle  
2. **Log Transform Target** – `SalePrice` → `log(SalePrice)`  
3. **Feature Selection** – starting with `GrLivArea` and `OverallQual`  
4. **Model Training** – Linear Regression from scikit-learn  
5. **Evaluation** – RMSE on validation set (log scale)  
6. **Predictions** – Convert back with exponential for submission  
7. **Create `submission.csv`** – for Kaggle leaderboard  

---

## 📈 Results
| Metric               | Value      |
|----------------------|------------|
| RMSE (log scale)     | *Your score* |
| R² (validation set)  | *Your score* |

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/house-price-prediction.git
cd house-price-prediction

# Open in Google Colab or Jupyter Notebook
