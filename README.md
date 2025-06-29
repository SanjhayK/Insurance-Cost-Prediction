# Insurance Cost Prediction Using Machine Learning

This project predicts individual medical insurance charges based on features like age, BMI, region, and smoking status. It uses regression models including:

- Linear Regression
- Ridge Regression
- Random Forest Regressor

## What’s Inside

- Exploratory data analysis and visualizations (e.g. age, BMI, smoker distribution)
- Manual encoding of categorical features
- Model training and evaluation using MAE, RMSE, and R²
- Feature importance analysis with Random Forest
- Prediction system for new insurance cost estimation

## Dataset

The dataset used contains demographic and health-related features of individuals, including:

- `age`, `sex`, `bmi`, `children`, `smoker`, `region`, and `charges`

## Tools & Libraries

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn

## File

- `Insurance_Cost_Prediction_Analysis.ipynb` – the full notebook with analysis and model training.

## Results:
Ridge and Linear Regression both performed similarly (MAE ≈ $28,500), while Random Forest captured more complex patterns but had slightly higher error (MAE ≈ $36,900).
---

Feel free to fork this repository or use it as a starter for deeper insurance pricing analysis.
