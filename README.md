
Nigeria Inflation Analysis: Macroeconomic Modeling & Regime Shifts (2003-2024)
📌 Project Overview
This repository contains an end-to-end data science pipeline analyzing the relationship between global crude oil dynamics and Nigerian inflation rates. The project moves beyond simple visualization to identify structural breaks in the economy using machine learning and econometric techniques.

🚀 Key Features
Time-Series Engineering: Merged disparate Year/Month data and implemented Linear Interpolation for data integrity.

Lagged Feature Analysis: Created 1-month and 3-month feature shifts to model the time-to-transmission of commodity shocks.

Regime Shift Detection: Utilized Rolling Correlations to prove a 2023 "Structural Break" in the Nigerian economy.

Predictive Modeling: Compared Linear Regression and Random Forest Regressors using non-shuffled Time-Series splits.

📊 Strategic Insights
The Production Paradox: Identified a strong inverse correlation (-0.72) between oil production and inflation, outweighing the impact of oil price itself.

Decoupling Signal: Post-2023, historical correlations failed, signaling a shift from commodity-driven to currency-driven inflation.

Feature Hierarchy: Random Forest analysis identified Food CPI as the leading anchor for headline inflation.

🛠️ Technical Stack
Language: Python 3.12

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Statsmodels

Environment: Jupyter Notebook / VS Code

Gotten from Kaggle data from IAMHARDY
