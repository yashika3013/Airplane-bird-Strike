# Airplane-bird-Strike
📌 Project Overview
This project analyzes wildlife collision data to determine factors affecting vehicle damage. We validate insights from Exploratory Data Analysis (EDA) using statistical tests.

📊 Dataset
Source: Kaggle - Airplane Bird Strikes


🔬 Objective
Bird strikes pose a significant risk to aviation safety, leading to potential damage, flight disruptions, and financial losses.
The goals of this analysis:
✅ Predict whether a bird strike will cause damage.
✅ Identify key risk factors (altitude, weather, aircraft type, wildlife species).
✅ Enhance safety by minimizing damage risks.
✅ Optimize costs by focusing on high-risk scenarios.
✅ Support regulatory compliance through data-driven risk assessments.

📊 Exploratory Data Analysis (EDA) Insights
✔ Most bird strikes do not cause damage, but severe cases exist.
✔ Takeoff & landing are the most vulnerable flight phases.
✔ Larger birds like Canada Goose pose higher risks.
✔ Strikes vary across locations, with some airports & states more affected.
✔ Larger aircraft with more engines offer better protection.
✔ Improved safety measures can reduce costs, disruptions, and enhance aviation safety.

📈 Statistical Validation of EDA
EDA insights were verified using statistical tests:
📌 Chi-square test → To assess relationships between categorical variables.
📌 ANOVA & t-tests → To compare means for numerical variables.

🤖 Model Development & Performance
The final model is a Voting Classifier combining:
✅ Decision Tree (DT)
✅ XGBoost (XGB)
✅ LightGBM

🔥 Performance Highlights
✔ Accuracy: 92%
✔ Recall: 54% (Future improvements will focus on recall to reduce false negatives.)
✔ Model is well-generalized and captures key patterns in bird strikes.

🚀 Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn)
Statsmodels & SciPy for statistical tests
Jupyter Notebook for analysis
