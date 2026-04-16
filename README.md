# RCEL-506
🚀 NASA Turbofan RUL Predictor
RCEL 506: Applied Statistics & Data Science for Engineering Leaders

📌 Project Overview

Briefly explain the goal: Using the NASA C-MAPSS dataset to predict the Remaining Useful Life (RUL) of turbofan engines. This app allows users to visualize sensor trends and see model predictions in real-time.

🛠️ Features

Interactive Dashboard: Explore sensor data (s1 to s21) across different engine units.

Baseline Comparison: View how the model performs against the mean-cycle benchmark (RMSE:46.11).

Predictive Analysis: Leverages a Random Forest Regressor to estimate engine failure points.

💻 How to Run

Clone the repository:

Bash
git clone https://github.com/your-username/your-repo-name.git
Install dependencies:

Bash
pip install -r requirements.txt
Launch the app:

Bash
streamlit run app.py
📊 Methodology

Data Source: NASA FD001 Dataset.

Target Variable: Max Cycles (Total Life).

Algorithm: Random Forest Regression (chosen for its ability to handle non-linear sensor correlations).

📝 Course Context

This project was developed for RCEL 506 at Rice University to demonstrate data-driven decision-making and the communication of complex analytical results to engineering stakeholders.

Reactive Task Completion

I have identified the key sections needed. I will not suggest adding a "Future Work" or "Known Issues" section unless you explicitly ask for them.
