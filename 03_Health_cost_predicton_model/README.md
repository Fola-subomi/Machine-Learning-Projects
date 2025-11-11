# Health Cost Prediction with Regression

## 📘 Overview
This project predicts individual medical insurance costs based on various demographic and health-related factors using regression analysis. It demonstrates how machine learning can be used to estimate healthcare expenses for insurance planning and risk assessment.

## 📊 Dataset
The dataset contains information such as:
- Age  
- Sex  
- BMI (Body Mass Index)  
- Number of children  
- Smoking status  
- Region  
- Insurance charges (target variable)

Source: [FreeCodeCamp - Predict Health Costs with Regression](https://www.freecodecamp.org/)

## 🧠 Methodology
1. **Data Preprocessing**
   - Handled missing values.
   - Encoded categorical features (sex, smoker, region).
   - Scaled numerical features.

2. **Exploratory Data Analysis**
   - Visualized distributions and correlations using heatmaps and pairplots.
   - Identified strong correlation between smoking and insurance charges.

3. **Modeling**
   - Implemented a **Linear Regression** model to predict insurance costs.
   - Split data into training and test sets for evaluation.

## 🧩 Model & Training
- Model: Linear Regression (from `scikit-learn`)
- Loss function: Mean Squared Error (MSE)
- Optimization: Ordinary Least Squares
- Evaluation Metrics: R² Score, MAE, RMSE

## 📈 Results
- Achieved an R² score of approximately **0.74**, indicating a good fit.
- Smoking status and age were found to be key predictors of cost.

## 🚀 Future Work
- Implement ensemble models (e.g., Random Forest, Gradient Boosting).
- Include additional socioeconomic or lifestyle features.
- Develop a web app for real-time cost prediction.

## ⚙️ Installation & Usage
```bash
git clone <repo-url>
cd health-cost-prediction
pip install -r requirements.txt
jupyter notebook fcc_predict_health_costs_with_regression.ipynb
