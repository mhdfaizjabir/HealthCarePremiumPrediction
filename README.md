## Healthcare Premium Prediction
This project predicts annual insurance premiums using machine learning techniques. It involves full-cycle data analysis, regression modeling, and result interpretation.

### Features:
- Data cleaning & outlier removal
- Risk score generation from medical history
- Feature encoding and VIF-based selection
- Regression models: Linear, Ridge, XGBoost
- Model evaluation using MSE/RMSE
- Post-hoc analysis of prediction errors
- Subgroup-specific model for users aged 25 or below
- Live prediction app using Streamlit

### Best Model:
- **XGBoost** (RMSE: ~1250)

### Special Insights:
- Majority of large errors occurred for users <25 years
- Suggested use of a subgroup model for this segment

### Tools:
- Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn, Streamlit, joblib


 [https://healthcarepremiumpredictionweb.streamlit.app](https://healthcarepremiumpredictions.streamlit.app)
