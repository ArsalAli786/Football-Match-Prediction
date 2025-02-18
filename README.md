# Football Match Outcome Prediction with EDA & Machine Learning

## 📌 Project Overview
This project analyzes football match data to identify key factors influencing match outcomes and builds predictive models for match results using machine learning techniques.

## 📂 Dataset
- **Source:** [European Soccer Database (Kaggle)](https://www.kaggle.com/datasets/hugomathien/soccer)
- **Tables Used:** `Match`, `Team`, `Player`, `Player_Attributes`, `Team_Attributes`, `Country`

## 🔍 Exploratory Data Analysis (EDA)
1. **Match Outcome Analysis:** Defined match results as 'Win', 'Loss', or 'Draw'.
2. **Seasonal Trends:** Analyzed goal counts and win rates by month/season.
3. **Team & Player Performance:** Identified top-performing teams and players.
4. **Anomaly Detection:** Found unusual matches with unexpected results.
5. **Home vs. Away Performance:** Compared win rates and performance metrics.

## 🛠 Feature Engineering
- Extracted relevant features (player skills, team attributes, recent form).
- Created new performance indicators.

## 🤖 Model Training & Evaluation
- **ML Models Used:**
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost
  - Support Vector Machine (SVM)
- **Evaluation Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- **Best Model:** XGBoost performed the best in predicting match outcomes.

## 🚀 Installation & Usage
### 1️⃣ Clone Repository
```bash
git clone https://github.com/yourusername/football-match-prediction.git
cd football-match-prediction
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run Analysis
Execute the Jupyter Notebook or Python scripts to perform data analysis and model training.

## 📊 Results & Insights
- **Home teams generally have a higher win probability.**
- **Key factors influencing match outcomes include team form, specific player attributes, and goal statistics.**
- **XGBoost was the most effective model for match result prediction.**

## 📜 License
This project is open-source under the [MIT License](LICENSE).

## 🔗 References
- [European Soccer Database (Kaggle)](https://www.kaggle.com/datasets/hugomathien/soccer)
- [Football Match Predictor (GitHub)](https://github.com/aziztitu/football-match-predictor)

---
💡 *Feel free to contribute! Fork the repo, raise issues, or suggest improvements.*
