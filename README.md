# 🛫 Flight Delay Prediction & AI Risk Analysis

A Machine Learning project that predicts flight delays using **Random Forest Classification** with an interactive **Power BI dashboard** for risk analysis and visualization.

---

## 📊 Project Overview

This project analyzes historical flight data to predict delays and provides actionable insights through an AI-powered dashboard. The model helps airlines and travelers make informed decisions based on delay probabilities.

---

## 🗂️ Repository Structure
```
├── Flight_Status_Prediction.ipynb          # Jupyter notebook with full ML pipeline
├── flight_status_prediction.py             # Python script for predictions
├── flight_delay_model.pkl                  # Trained Random Forest model (8.06 MB)
├── airline_encoder.pkl                     # Label encoder for airline data
├── Flight Delay Prediction & AI Risk Analysis Dashboard.pbit  # Power BI template
├── Flight Delay Prediction & AI Risk Analysis Dashboard.pdf   # Dashboard export
├── requirements.txt                        # Python dependencies
└── .gitignore                              # Excludes large datasets
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Power BI Desktop (for dashboard)

### Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/sneha-gitv13/Flight-Delay-Prediction-AI-Dashboard.git
   cd Flight-Delay-Prediction-AI-Dashboard
```

2. **Install dependencies:**
```bash
   pip install -r requirements.txt
```

3. **Run the prediction script:**
```bash
   python flight_status_prediction.py
```

4. **Open the Jupyter Notebook:**
```bash
   jupyter notebook Flight_Status_Prediction.ipynb
```

---

## 🧠 Model Details

- **Algorithm:** Random Forest Classifier
- **Model Size:** 8.06 MB
- **Features:** Flight timing, airline data, routes, historical patterns
- **Preprocessing:** Label encoding for categorical variables

---

## 📈 Power BI Dashboard

The interactive dashboard provides:
- ✈️ Real-time delay predictions
- 📊 Risk analysis by airline, route, and time
- 🎯 Key performance indicators (KPIs)
- 📉 Historical trend analysis

**To use the dashboard:**
1. Open Flight Delay Prediction & AI Risk Analysis Dashboard.pbit in Power BI Desktop
2. Connect to your data source
3. Refresh to see live predictions

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Core programming language |
| **Scikit-learn** | Random Forest implementation |
| **Pandas & NumPy** | Data manipulation |
| **Joblib** | Model serialization |
| **Power BI** | Interactive visualization |
| **Jupyter Notebook** | Development environment |

---

## 📁 Dataset

The training dataset is **not included** in this repository due to size constraints (excluded via .gitignore). 

To use your own data:
1. Prepare a CSV with flight features (airline, departure time, route, etc.)
2. Update file paths in the notebook
3. Retrain the model if needed

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📧 Contact

**Author:** Sneha  
**GitHub:** [@sneha-gitv13](https://github.com/sneha-gitv13)  
**Project Link:** [Flight-Delay-Prediction-AI-Dashboard](https://github.com/sneha-gitv13/Flight-Delay-Prediction-AI-Dashboard)

---

## ⭐ Show Your Support

If you find this project useful, please consider giving it a star! ⭐

---

## 📝 License

This project is open source and available for educational purposes.
