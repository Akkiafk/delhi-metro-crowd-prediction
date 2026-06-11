# Delhi Metro Crowd Prediction

A machine learning project that predicts crowd levels (Low / Medium / High) at Delhi Metro stations using historical passenger data.

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## Results

| Model | Accuracy |
|---|---|
| Logistic Regression | ~81% |
| Decision Tree | ~92% |
| Random Forest | ~91% |
| XGBoost | ~97% |

## Features
- Day of week, day of month, month
- Is weekend flag
- Previous day demand (lag feature)
- 3-day and 7-day rolling average
- Per-station encoding

## Dataset
Delhi Metro passenger data with origin-destination station info and daily passenger counts.

## How to Run
1. Clone the repo
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Run the notebook `mlodaproject.ipynb` in Google Colab or Jupyter

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Matplotlib
