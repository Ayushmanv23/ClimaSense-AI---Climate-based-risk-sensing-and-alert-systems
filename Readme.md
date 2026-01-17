# Project Title - **ClimaSense AI – Climate-Based Disease Risk Sensing and Alert System**

---

## Brief One Line Summary
An AI-driven system that analyzes real-time climate and air quality data to warn users about potential disease risks before they spread.

---

## Overview
ClimaSense AI is a preventive health awareness platform that integrates real-time environmental data with machine learning models to assess health risk levels. The system interprets air quality and weather conditions from a health perspective and provides early warnings through a web dashboard and email alerts.  
It is designed to support **early awareness and preventive decision-making**, not medical diagnosis.

---

## Problem Statement
Air pollution and changing climatic conditions significantly increase the risk of respiratory and climate-sensitive diseases. Although real-time environmental data is available, it is often presented in raw numerical form and lacks health-oriented interpretation.  
There is a need for a system that can convert environmental data into understandable health risk alerts for timely preventive action.

---

## Dataset
- Real-time **Air Quality Data** (AQI, PM2.5, PM10)
- Real-time **Weather Data** (Temperature, Humidity, Rainfall, Wind Speed, Pressure)
- Data collected dynamically using external APIs
- Historical patterns used for model training and validation

---

## Tools and Technologies
- **Programming Language:** Python  
- **Machine Learning:** XGBoost  
- **Data Processing:** Pandas, NumPy  
- **Frontend:** Streamlit  
- **APIs:** Weather and Air Quality APIs  
- **Alerts:** Email Notification System  

---

## Flow - ClimaSense-AI
│
├── README.md                      # Project documentation
├── .gitignore                     # Git ignored files
├── requirements.txt               # Python dependencies
├── Report.pdf                     # Project report (minor project)
│
├── data/                          # Data handling
│   ├── historical_data.csv        # Historical environmental data
│   └── sample_inputs.json         # Sample API responses
│
├── notebooks/                     # Jupyter notebooks
│   ├── exploratory_data_analysis.ipynb
│   └── model_training.ipynb
│
├── models/                        # Trained ML models
│   └── xgboost_health_model.pkl
│
├── scripts/                       # Core Python logic
│   ├── data_collection.py         # API data fetching
│   ├── data_preprocessing.py      # Cleaning & feature engineering
│   ├── risk_prediction.py         # ML prediction logic
│   └── alert_service.py           # Email alert system
│
├── dashboard/                     # Web application
│   └── app.py                     # Streamlit dashboard
│
└── utils/                         # Helper utilities
    └── config.py                  # API keys & configurations


## Methods
1. Real-time data collection from air quality and weather APIs  
2. Data preprocessing (cleaning, normalization, feature selection)  
3. Machine learning-based risk prediction using XGBoost  
4. Epidemiological rule-based validation  
5. Health risk classification (Low / Medium / High)  
6. Email alert generation for medium and high-risk conditions  

---

## Key Insights
- High PM2.5 and PM10 levels strongly correlate with elevated health risk
- Combining weather and air quality improves risk assessment accuracy
- Rule-based validation enhances model reliability
- Early warnings are more effective than post-symptom awareness

---

## Dashboard / Model / Output
- Interactive Streamlit dashboard
- Displays real-time environmental conditions
- Shows predicted health risk level
- Identifies likely climate-related diseases
- Email alerts triggered for medium and high risk
- Output is **risk-oriented**, not disease diagnosis

---

## How to Run this Project?
```bash
# Clone the repository
git clone https://github.com/your-username/ClimaSense-AI.git

# Navigate to project directory
cd ClimaSense-AI

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py

#Contact
Ayushman Vohra (Student)
Email: ayushmanvohra7@gmail.com
[Linkedin] (https://www.linkedin.com/in/ayushman-vohra/)
[My Webpage] (https://ayushmanvohra7.wixsite.com/ayushman23)
[My IG] (https://www.instagram.com/itsayushman_23?igsh=MXRlNnl5cmRsY2M0Mg==)


