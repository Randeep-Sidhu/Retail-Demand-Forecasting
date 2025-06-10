# 🛍️ Retail Demand Forecasting
## 📌 Overview
This project uses machine learning to predict weekly sales for retail stores (45 stores, ~100 departments, 2010–2013) to optimize stock levels. The pipeline includes EDA, preprocessing, feature engineering, and modeling with Random Forest.

### 🧠 Key Steps
- ** 🔍 EDA**: Identified sales spikes during holidays, handled missing MarkDowns.
- ** 🧹 Preprocessing**: Cleaned data, encoded categoricals, capped outliers.
- ** 🏗️ Feature Engineering**: Added temporal features, holiday flags, sales lags, target-encoded Store/Dept.
- ** 🤖 Modeling**: Random Forest (RMSE ~$3,306.65, R² ~0.9747).
- **Deliverables**: Notebook, presentation PDF, sample dataset.

## Setup
1. Clone repo: `git clone https://github.com/yourusername/Retail-Demand-Forecasting.git`
2. Install dependencies: `pip install pandas sklearn matplotlib seaborn joblib nbconvert`
3. Open `Retail_Demand_Forecasting.ipynb` in Jupyter/VS Code.

## 📈 Results
- **Top Features**: Lag_1, Lag_4, Dept_Encoded, Week, CPI (indicating past sales, department, and economic factors drive predictions).
- **Presentation**: [Retail Demand Forecasting.pdf](Retail Demand Forecasting.pdf)



## 🚀 Future Work
- Tune hyperparameters, try XGBoost, deploy API.

*by 👨‍💻 Randeep Sidhu*
