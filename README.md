# Causal-Impact-Medicaid-Python
I analyzed the causal impact of Medicaid expansion on U.S. healthcare coverage using Python, applying DiD and Event Study methods to derive policy insights.

Impact Evaluation of Medicaid Expansion on Healthcare Coverage (Python)
This repository analyzes the causal impact of the Affordable Care Act's (ACA) Medicaid expansion on U.S. healthcare coverage across diverse demographic groups, using rigorous econometric methods.

📝 Project Overview
A Master's project demonstrating causal inference in public policy through real-world observational data.

🎯 Objectives
Estimate Medicaid expansion's causal effect on health insurance and Medicaid coverage.

Analyze impact disparities across poverty and demographic factors.

Apply and test Difference-in-Differences (DiD) and Event Study methodologies.

Generate policy insights on healthcare access inequities.

⚙️ Methodology
Analysis uses U.S. individual-level survey data (usa_00019.csv). My approach involved:

Data Preparation: Cleaning, recoding, and feature engineering with pandas.

Difference-in-Differences (DiD): Implemented DiD regression using Medicaid_expansion, POST_TREATMENT, and DID variables.

Event Study Analysis: Created interaction terms for pre/post-policy trends visualization.

Assumption Testing: Rigorously tested parallel trends assumption with visual inspection and formal F-tests.

Control for Confounders: Included socioeconomic and demographic variables in models.

🛠️ Technologies & Tools
Python: Primary programming language.

Pandas: Data manipulation.

Statsmodels: OLS and econometric modeling (DiD, Event Study).

Matplotlib: Regression result visualization.

🏃 How to Run the Project
Clone the repository: git clone https://github.com/Sametcan99/Medicaid-Expansion-Impact-Eval-Python.git

Navigate: cd Medicaid-Expansion-Impact-Eval-Python

Dataset: Place usa_00019.csv in the project directory.


📈 Key Findings & Insights
Medicaid expansion significantly increased both overall health insurance coverage and Medicaid enrollment.

Impact varied across subgroups, highlighting persistent disparities.

Parallel trends assumption testing strongly supported causal interpretations.

📞 Contact
Feel free to connect:

LinkedIn: https://www.linkedin.com/in/sametcan-kandemirt/

Email: kandemirsametcan99@gmail.com
