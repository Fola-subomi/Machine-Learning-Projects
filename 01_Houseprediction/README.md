# 🏠 House Price Prediction

## 📘 Overview
This project predicts the **price of houses** based on features such as number of rooms, area, location, and other parameters.  
It’s a classic regression problem demonstrating how to use **Machine Learning** for numerical prediction.

---

## 🎯 Objectives
- Understand how to load, clean, and preprocess data.  
- Train and evaluate regression models.  
- Compare different algorithms (Linear Regression, Random Forest).  
- Visualize relationships between housing features and price.

---

## 📊 Dataset
- **Source:** [Scikit-learn’s Boston Housing Dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html)
- **Features include:**
  - `RM` — Average number of rooms per dwelling  
  - `LSTAT` — % of lower status population  
  - `PTRATIO` — Pupil-teacher ratio  
  - `TAX` — Property tax rate  
  - `MEDV` — Median value of owner-occupied homes (target)

---

## ⚙️ Models Used
- **LHistGradientBoostingRegressor**

---

## 📈 Results
| Model | R² Score | RMSE |
|-------|-----------|------|
| HistGradientBoostingRegressor | 0.89|

---

## 🧰 Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## ▶️ How to Run
```bash
# Clone the repository
git clone https://github.com/PreciousAkogun/ml-projects.git
cd house-price-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook notebooks/house_price_prediction.ipynb


