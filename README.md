# ⚡ Electricity Hourly Demand Prediction

This project focuses on accurately forecasting hourly electricity demand using machine learning techniques. It aims to help power grid operators optimize energy distribution and proactively balance supply and demand.

---

## 📌 Problem Statement

How can we predict electricity demand on an **hourly basis** to ensure steady power distribution, avoid shortages, and improve energy efficiency?

A centralized electricity station must manage incoming power and forecast consumption to avoid overloads or shortages. An hourly demand prediction system can support real-time decision-making for energy allocation.

---

## Project Report 

[Energy demand Hourly prediction](https://drive.google.com/file/d/1b6ICx0mDXsNKpDGFgWnCqpUsDfQQk7sU/view?usp=sharing)

---

## 📊 Dataset

- Real-world electricity consumption data (hourly granularity)
- Includes features like:
  - Hour of the day
  - Day of the week
  - Temperature
  - Historical usage
  - Weather conditions

---

## 🧠 Approach

1. **Data Preprocessing**
   - Missing value handling
   - Feature engineering (e.g., time lags, rolling stats)
   - Normalization/scaling

2. **Model Development**
   - Explored various time series and regression models:
     - Linear Regression
     - Random Forest
     - XGBoost
     - LSTM (for deep learning approach)
   - Evaluated models using RMSE, MAE, and MAPE

3. **Model Deployment**
   - In streamlit where users can enter values for specific hour 
   - And predict the demand for next hour
   - Either surplus or demand 

---

## ⚙️ Tech Stack

- **Python**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn**, **XGBoost**
- **Jupyter Notebook / VS Code**

---

## 📈 Results

- Achieved **~30% improvement in forecasting accuracy** compared to baseline.
- Reduced supply-demand mismatch risk by **proactive load forecasting**.
- Successfully handled real-time data with temporal dependencies.

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/electricity-demand-prediction.git
cd electricity-demand-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Electricity_Demand_Prediction.ipynb
```
---

## 📌 Future Enhancements

- Real-time dashboard using **Streamlit** or **Dash**
- Integrate renewable energy prediction (solar/wind)
- Cloud deployment for live monitoring

---

## 🤝 Acknowledgements

This project was inspired by real-world grid management problems and represents a self-initiated solution to enhance energy forecasting in power distribution systems.

---

## 📬 Contact

📧 [mohammedkayser143@gmail.com]  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/mohammedkayser/)

