# Airplane-bird-Strike
📌 Project Overview
This project analyzes wildlife collision data to determine factors affecting vehicle damage. We validate insights from Exploratory Data Analysis (EDA) using statistical tests.

📊 Dataset
Source: https://www.kaggle.com/datasets/ulrikthygepedersen/airplane-bird-strikes/data

🔬 Objective
Bird strikes pose a significant risk to aviation safety, leading to potential damage, flight disruptions, and 
financial losses. The goal of this analysis is to predict whether a bird strike will cause damage to an aircraft 
based on various factors such as altitude, weather conditions, aircraft type, and wildlife species. 
The primary objectives are to develop a model to classify bird strike incidents, enhance safety by reducing 
damage risks, optimize costs by targeting high-risk scenarios, and support regulatory compliance through 
data-driven risk assessments.

📊 Exploratory Data Analysis (EDA) Insights
✔ Most bird strikes do not cause damage, but severe cases exist.
✔ Takeoff & landing are the most vulnerable flight phases.
✔ Larger birds like Canada Goose pose higher risks.
✔ Strikes vary across locations, with some airports and states more affected.
✔ Larger aircraft with more engines offer better protection.
✔ Improved safety measures can reduce costs, disruptions, and enhance aviation safety.

📈 Statistical Validation of EDA
EDA insights were verified using statistical tests to ensure reliability:
Chi-square test for categorical variable relationships.
ANOVA & t-tests to compare means for numerical variables.

Model Development & Performance
The final model is a Voting Classifier combining:
✅ Decision Tree (DT)
✅ XGBoost (XGB)
✅ LightGBM

🔥 Performance Highlights
Model is well-generalized and captures key patterns.
Accuracy: 92%
Recall: 54%
Recall is relatively lower, which can be concerning for safety-critical decisions. Future improvements will focus on enhancing recall to reduce false negatives.

🚀 Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn)
Statsmodels & SciPy for statistical tests
Jupyter Notebook for analysis
