# Premier League Match Predictor

A machine-learning project that predicts Premier League match outcomes:
home win, draw, or away win.

## Technologies

Python, pandas, scikit-learn, Jupyter Notebook

## Methods

- Multinomial logistic regression
- Elo team ratings
- One-hot encoding for team names
- Standard scaling and median imputation
- Class-balanced model training
- Time-based train/test evaluation

## Features

The model uses only information available before each fixture:

- Recent five-match form
- Recency-weighted form
- Home and away form
- Current-season points, games played, and goal difference
- Elo ratings
- Head-to-head history
- Team identity and home advantage

## Results

On a held-out set of 2026/27 Premier League matches, the model achieved approximately 48% accuracy.

This exceeded an always-predict-home-win baseline of approximately 36%.

## Running the Project

1. Clone the repository.
2. Create and activate a virtual environment.
3. Install dependencies:

```bash
pip install -r requirements.txt
