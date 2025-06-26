# 🚗 CO₂ Emissions Predictor Using Vehicle Specs

This project supports **UN SDG 13: Climate Action** by using machine learning to predict vehicle CO₂ emissions based on car specifications. It empowers consumers and policymakers to make environmentally informed decisions.

## 🔍 Objective
To forecast CO₂ emissions using vehicle features like make, model, engine size, and class—helping reduce transportation-related carbon footprints.

## 🧠 Machine Learning Approach
- **Type**: Supervised Learning (Linear Regression)
- **Features**: Make, Model, Vehicle Class, Engine Size(L)
- **Target**: CO₂ Emissions(g/km)
- **Tools**: Python, Pandas, Scikit-learn, Matplotlib

## 📊 Results
- **Mean Absolute Error (MAE)**: _XX.XX_  
- **R² Score**: _0.XX_  
- Visual comparison of actual vs predicted emissions saved in `images/model_output.png`.

## 📁 Project Structure

## 🚀 How to Run
1. Clone this repository  
2. Install dependencies:  
3. Run the notebook:  
Open `CO2_predictor.ipynb` in Jupyter Notebook or VS Code

## 🧼 Ethical Considerations
The model is trained on a diverse dataset of vehicle types, but may not fully represent electric or hybrid vehicles. Future iterations could include fuel type and consumption for improved fairness.

## ✨ Future Enhancements
- Deploy as a Streamlit web app  
- Add fuel type and consumption metrics  
- Compare multiple regression models for better accuracy