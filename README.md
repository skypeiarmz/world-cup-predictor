# World Cup Match Outcome Predictor

Predicts the outcome (Win / Draw / Loss) of international football matches 
using 150 years of FIFA data and a machine learning classifier.

**Live demo:** [link when deployed]

## Tech stack
Python · Pandas · Scikit-learn · Streamlit

## Setup
```bash
git clone https://github.com/YOUR_USERNAME/world-cup-predictor.git
cd world-cup-predictor
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
```

## Data
Download from [Kaggle](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)
and place `results.csv` in `data/raw/`.

## Run
```bash
streamlit run app.py
```