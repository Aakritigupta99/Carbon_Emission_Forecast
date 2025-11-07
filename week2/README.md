# 📊 Model Results — Carbon Emission Prediction (Week 2)

## 🔍 Overview
This folder contains all the **model outputs and visualizations** for the project **"Carbon Emission Prediction using AI/ML"**.  
The model predicts annual CO₂ emissions using population, energy consumption, and fertilizer usage data.

---

## ⚙️ Model Information
- **Algorithm Used:** XGBoost Regressor  
- **Training/Test Split:** 80/20  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib  
- **Runtime Environment:** Google Colab  

---

## 📈 Model Performance

| Metric | Value |
|---------|--------|
| **R² Score** | 0.9451 |
| **Accuracy** | 94.51% |
| **Mean Squared Error (MSE)** | 1.296 × 10¹⁷ |

✅ The model achieved **94.5% accuracy**, showing excellent prediction capability for carbon emission forecasting.

---

## 🖼️ Visual Outputs

| Chart | Description |
|--------|--------------|
| ![CO₂ Emission Trend](CO2_Emission_Trend.png) | Global CO₂ emissions trend over time |
| ![Actual vs Predicted](Actual_vs_Predicted.png) | Comparison of actual vs predicted emission values |
| ![Feature Importance](Feature_Importance.png) | Top features contributing to the model |

---

## 📂 Files in This Folder

results/
├── carbon_emission_model.pkl # Trained XGBoost model file
├── accuracy_report.txt # Model performance summary
├── CO2_Emission_Trend.png # Emission trend visualization
├── Actual_vs_Predicted.png # Actual vs Predicted output chart
└── Feature_Importance.png # Feature importance chart


---

## 🧠 Summary
- Combined multiple datasets: **Population, Energy Use, Fertilizer vs GDP**.  
- Improved model performance from **66% → 94.5% accuracy**.  
- Used feature scaling, data cleaning, and XGBoost optimization.  
- All results and visuals are generated automatically in the Colab notebook.

---

## 🪄 Next Steps
- Integrate chatbot using **Gradio** for user input and live predictions.  
- Enhance visualization with interactive dashboards.  
