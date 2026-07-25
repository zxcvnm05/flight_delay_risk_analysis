# flight_delay_risk_analysis

## 📌 Executive Summary
This study quantifies operational uncertainty in airline flight delays using statistical distribution fitting and Monte Carlo simulations, combined with Machine Learning classifiers. The model evaluates Risk Management Options (RMOs) and predicts high-risk flights before departure to mitigate severe delay tails.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** NumPy, SciPy, Scikit-learn, Pandas, Matplotlib, Seaborn
- **Methodologies:** Event Tree Analysis, K-S & A-D Goodness-of-Fit Tests, Monte Carlo Simulation (100,000 iterations)

## 📂 Project Structure
├── data/               # 2024 Kaggle flight dataset
├── notebooks/          # Distribution fitting, Monte Carlo simulation, and ML training
├── outputs/            # Simulation distribution plots, ROC-AUC curves, event trees
└── README.md           # Project documentation

## 🚀 Key Results & Findings
- **Distribution Fit:** Confirmed Exponential distribution for delay magnitude using K-S and A-D tests.
- **Uncertainty Reduction:** Simulated Risk Management Options (RMOs) reduced mean delay from **14.03 to 6.58 minutes**.
- **Predictive Accuracy:** Machine Learning classifiers (Logistic Regression, Decision Tree) achieved **AUC > 0.89** in predicting high-risk flights (> 60 min delay).

## 💼 Business Impact & Recommendations
- **Proactive Interventions:** Integrates real-time weather and maintenance intelligence into pre-departure risk scoring.
- **Tail Risk Mitigation:** Reduces severe operational disruptions and passenger compensation costs.
