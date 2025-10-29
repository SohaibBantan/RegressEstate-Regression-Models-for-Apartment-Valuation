# 🏙️ RegressEstate: Regression Models for Apartment Valuation
**Author:** Sohaib Bantan  
**Last Updated:** October 2025  

---

## 🧠 Overview
**RegressEstate** is an interactive, end-to-end **machine learning project** that predicts apartment prices using structured (tabular) data.  
It combines data preprocessing, model selection, training, evaluation, and user interaction — all in one notebook.

Users can **choose a model**, visualize performance, and even **enter apartment details manually** to get real-time price predictions.

---

## 🚀 Features
- **Data Preprocessing:**  
  Handles missing values, encodes categorical variables, and scales numerical features using `ColumnTransformer`.

- **Model Selection:**  
  Interactive dropdown lets the user choose one of three models:
  - Linear Regression  
  - HistGradientBoostingRegressor  
  - Keras Neural Network (Feedforward MLP)

- **Model Evaluation:**  
  Automatically computes:
  - RMSE (Root Mean Squared Error)  
  - MAE (Mean Absolute Error)  
  - R² Score  
  - Accuracy within ±10%

- **Visualizations:**  
  - Predicted vs Actual Prices  
  - Residuals Plot  
  - Error Distribution  
  - Neural Network Loss Curve (for Keras model)

- **Manual Prediction:**  
  Users can manually enter apartment features (size, rooms, city, etc.) to get an instant price prediction.

---

## ⚙️ Setup Instructions

1. **Open the notebook**  
   - You can run this project in **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.  
   - File: `Apartment_Price_Prediction_Project.ipynb`

2. **Install the required libraries**  
   Run this in a new cell (or your terminal):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow ipywidgets
Run all cells in order

When prompted, select a model (Linear Regression, HistGradientBoosting, or Keras Neural Network).

Wait for training and visualizations to appear.

Use the manual input section at the end to enter apartment details and get a predicted price 💰.

That’s it! The notebook is fully self-contained — no special setup or configuration needed.


## 🏁 Conclusion

This project demonstrates a complete, interactive machine learning workflow — from data preprocessing to model evaluation and real-time prediction.  
It serves as a solid foundation for more advanced real estate price prediction systems and showcases practical ML engineering skills.

If you found this useful or inspiring, feel free to ⭐ star the repo and explore the notebook!
