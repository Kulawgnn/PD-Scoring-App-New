# PD Scoring App (Ghana)

A machine learning app to estimate the probability of loan default using behavioral, financial, and economic indicators in Ghana.

## How to Run
Install dependencies:

```
pip install -r requirements.txt
```

Then launch the app:

```
streamlit run pd_scoring_app_with_score.py
```

## Files
- `pd_model_with_creditscore.pkl` - Trained Random Forest model
- `scaler_with_creditscore.pkl` - StandardScaler used for preprocessing
- `enhanced_pd_with_credit_score.csv` - Simulated dataset
- `pd_scoring_app_with_score.py` - Streamlit application