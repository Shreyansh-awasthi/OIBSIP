# Car Price Prediction

## 📌 Project Overview
This project builds a Machine Learning regression model to predict the **selling price of used cars** based on features like car age, fuel type, transmission, kilometers driven, and more.

## 📊 Dataset
Car sales dataset containing features such as:
- Car Name / Brand
- Year of Manufacture
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type (Petrol/Diesel/CNG)
- Transmission Type
- Number of Owners

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn (visualization)
- Scikit-learn (model building)

## 🔍 Workflow
1. **Data Cleaning** — handled missing values and derived new features (e.g., car age from manufacture year).
2. **Exploratory Data Analysis (EDA)** — visualized relationships between selling price and features like fuel type, car age, and kilometers driven.
3. **Feature Engineering** — encoded categorical variables (fuel type, transmission, seller type).
4. **Model Building** — trained regression models (e.g., Linear Regression / Random Forest / Lasso) to predict selling price.
5. **Model Evaluation** — evaluated using R² score and error metrics (MAE/MSE).

## ✅ Results
The model successfully predicts car selling prices with strong correlation to features like present price, car age, and fuel type — diesel and newer cars generally commanding higher resale value.

## 📁 Files
- `Car_price_prediction.ipynb` — Jupyter notebook with full code, visualizations, and model training
- `README.md` — Project documentation

## 🚀 How to Run
1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Open `Car_price_prediction.ipynb` in Jupyter Notebook / VS Code and run all cells

## 🎯 Internship
This project was completed as **Task 3** of the Data Science internship at **Oasis Infobyte**.
