Black–Scholes Option Pricing with Machine Learning
Predicts European call and put option prices by combining the Black–Scholes formula with Random Forest Regression.
Generates synthetic option pricing data from financial theory and optimizes ML models for high accuracy.

Key Features
Synthetic data generation via Black–Scholes.

Separate ML models for Call & Put options.

RandomizedSearchCV for hyperparameter tuning.

Performance metrics: R², MAE, RMSE.

Workflow
Generate synthetic option prices (S, K, T, r, σ).

Train Random Forest models for call & put options.

Tune parameters using RandomizedSearchCV (3-fold CV).

Retrain on full data & evaluate performance.

Achieve improved predictive accuracy over baseline.

📊 Example Results
Model	R² Score	MAE	RMSE
Call Option	0.99+	Low	Low
Put Option	0.99+	Low	Low

Quick Start
bash
Copy
Edit
git clone https://github.com/soham12amgh/Predicting-European-option-prices-using-RFA
cd black-scholes-ml
pip install -r requirements.txt
jupyter notebook Black-Scholes-ML.ipynb
Requirements: Python 3.x, NumPy, Pandas, Matplotlib, Scikit-learn

 Applications
Financial ML education

Option pricing prototyping

Synthetic data research

