Hybrid Analytical Engine for AI-HRM Analysis
Recovering the Anxiety–Safety Paradox in Organizational Innovation
This repository contains the Python implementation of the Four-Stage Hybrid Analytical Engine, a methodological framework designed to detect behavioral signals in noisy, proxy-based HR datasets. This research introduces the concepts of Digital Friction and the Anxiety–Safety Paradox.

🚀 Research Overview
Traditional linear models often fail to capture the complex dynamics of AI-mediated workplaces. 
This project utilizes a dual-stream approach (Simulated vs. Empirical) to demonstrate how non-linear signals can be recovered even when linear explanatory power (R^2) is near zero.

The Four Stages:
            Stage I: OLS Baseline – Establishing the linear "noise floor."
            Stage II: PCA/PCR Recovery – Extracting the Digital Friction profile (the mathematical fusion of AI adoption and Technology Anxiety).
            Stage III: ML Signal Recovery – Utilizing Random Forest and XGBoost to identify top behavioral drivers.
            Stage IV: SHAP Explainability – Validating model logic against theoretical SEM coefficients (The "Truth Bridge").

📁 Repository Structure
The analysis is broken down into modular notebooks for clarity:
          Stage_1_Baseline_OLS.ipynb: Linear regression and diagnostic checks.
          Stage_2_PCA_DigitalFriction.ipynb: Principal Component Analysis and Latent Profile extraction.
          Stage_3_ML_Predictive_Recovery.ipynb: Random Forest and XGBoost training/evaluation.
          Stage_4_SHAP_Convergence.ipynb: Global attribution values and SEM vs. SHAP convergence plots.

📊 Key Findings
The Anxiety–Safety Paradox: While Psychological Safety is a theoretical enabler, Technology Anxiety acts as the dominant empirical constraint in real-world settings.
Digital Friction: AI_HRM adoption and Technology Anxiety load almost identically on the primary latent component (PC1), suggesting they are psychologically inseparable for employees.

🛠️ Requirements
To run these notebooks, you will need:
Python 3.8+,pandas, numpy, scikit-learn, xgboost, shap, matplotlib, seaborn

✍️ Author
Okechukwu Chinyere Perpetua Academic Technologist & Data Analyst Department of Statistics, Abia State Polytechnic, Aba.

📜 Citation
If you use this framework or the Digital Friction construct in your research, please cite:

Perpetua, O. C. (2026). Beyond the Linear Noise Floor: Recovering the Anxiety–Safety Paradox in AI-Enabled HRM Systems.
