# 📘 Duolingo Product Analytics & Churn Prediction

End-to-End AARRR Case Study | 10,000 Users | Python | Jupyter | A/B Test | ML Churn Model

This is a complete product analytics case study built for a Duolingo-like app using synthetic data for 10,000 users.

It covers:

🔵 Acquisition → DAU, WAU, MAU

🟠 Activation → XP, lessons, streaks

🟣 Retention → Cohorts, D1/D7/D30, churn model

🟡 Revenue → A/B test on paywall conversion

🟢 Referral proxy → Engagement segments

🧠 Churn prediction model (Logistic Regression)

📊 7 visualizations + full Jupyter notebook

This project simulates a real product analyst workflow used at Duolingo, Meta, Uber, etc.

## 📂 Project Structure

duolingo_analysis_project/
│
├── data/
│   ├── users.csv
│   ├── sessions.csv
│   ├── lessons.csv
│   ├── retention.csv
│   └── ab_test.csv
│
├── notebook/
│   └── duolingo_analytics.ipynb
│
├── reports/
│   ├── figures/
│   │   ├── ab_test_results.png
│   │   ├── churn_feature_importance.png
│   │   ├── cohort_heatmap.png
│   │   ├── lessons_distribution.png
│   │   ├── retention_line.png
│   │   ├── streak_distribution.png
│   │   └── xp_distribution.png
│   └── Duolingo_AARRR_Report.pdf
│
├── README.md


## 📊 Key Metrics Summary

Engagement
Metric	Value
DAU	188.81
WAU	826
MAU	2353.2
Stickiness	22.86%
Retention (Cohort-Based)

Day 1 Retention: 55.58%

Day 7 Retention: 17.94%

Day 30 Retention: 28.87%

A/B Test (Paywall Conversion)
Group	Conversion
Control (A)	5.6%
Variant (B)	8.34%

➡ Variant improves conversion by ~48.9%
➡ p-value = 7.09e-08 (statistically significant)
➡ Rollout recommended

Churn Prediction Model

Model Accuracy: 51.9%

Top predictors of churn:

Country (Mexico, Philippines, Germany)

Language (Spanish lowers churn)

XP Earned

Streak length

Age Group 35–44

## 🔍 Insights & Recommendations

⭐ 1. Improve Onboarding for High-Churn Countries

Users from Mexico & Philippines show higher churn → add localized content/tutorials.

⭐ 2. Boost Streak Motivation

Streak is a strong anti-churn factor → add streak boosts, rewards, social streaks.

⭐ 3. Optimize XP Rewards

Low XP sessions correlate with churn → redesign micro-lessons or reward structure.

⭐ 4. Roll Out Paywall Variant B

It increases conversion significantly → expected revenue lift.

⭐ 5. Personalize Content by Language

Spanish learners retain better → model suggests language-based segmentation.

## 🚀 How to Run the Project

1. Clone the repo
git clone https://github.com/Navodya-Jain/duolingo_analysis_project.git

2. Create virtual environment
python -m venv venv

3. Activate environment

Windows:

venv\Scripts\activate


Mac/Linux:

source venv/bin/activate

4. Install dependencies
pip install -r requirements.txt

5. Run Jupyter Notebook
jupyter notebook

## 🧰 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn, Plotly

SciPy

Scikit-learn

Jupyter Notebook

## 📘 Author

Navodya Jain
Product Analyst | Data Storytelling 
GitHub: Navodya-Jain

## ⭐ Give a Star!

If you like the project, ⭐ star the repo!