

# 🌸 Iris Flower Classification

## 📘 Overview
This project classifies **Iris flowers** into three species — *Setosa*, *Versicolor*, and *Virginica* — based on sepal and petal dimensions.  
It’s one of the most famous beginner-friendly datasets in Machine Learning.

---

## 🎯 Objectives
- Explore and visualize the Iris dataset.  
- Train a classifier to predict flower species.  
- Evaluate accuracy of multiple algorithms.

---

## 📊 Dataset
- **Source:** [Scikit-learn Iris Dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html)
- **Features:**
  - `sepal length (cm)`
  - `sepal width (cm)`
  - `petal length (cm)`
  - `petal width (cm)`
- **Target:** Species (Setosa, Versicolor, Virginica)

---

## ⚙️ Model Used
- Logistic Regression  

---

## 📈 Results
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 96% |

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
cd iris-classification

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook notebooks/iris_classification.ipynb
