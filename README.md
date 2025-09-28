# 📊 AI-Powered Student Engagement & Retention

This project explores how AI-driven analytics can help educational platforms boost student engagement and reduce dropout rates. Conducted over a four-week virtual internship, the initiative transformed raw learner data into actionable insights and personalized interventions.

---

## 🚨 Problem Statement

Despite rising enrollments in online programs, student retention remains critically low. Many learners sign up but fail to complete courses, leading to wasted resources and diminished impact. This project aimed to:

- Understand patterns of engagement and dropout
- Predict at-risk learners using machine learning
- Design a recommendation system for personalized support
- Provide strategic recommendations to improve retention

---

## 🛠️ Step-by-Step Actions

### Data Preprocessing & Feature Engineering
- Removed duplicates, standardized dates, normalized categories
- Engineered features: age, program duration, dropout flag
- Tools: Python (Pandas, NumPy), SQL

### Exploratory Data Analysis (EDA)
- Time-series analysis of signups and completions
- Visualized trends using Power BI and Tableau
- Segmented learners by demographics and behavior

### Churn Analysis & Predictive Modeling
- Built models: Logistic Regression, Decision Trees, Random Forest
- Evaluated performance using precision, recall, F1-score, accuracy
- Best model: Random Forest (~79% accuracy)

### Recommendation System Design
- Developed content-based filtering system
- Suggested courses based on learner history
- Triggered nudges for inactive learners
- Tools: Python (scikit-learn)

---

## 🔍 Key Insights & Approach

- 📈 Signups peaked in August 2023 and January 2024, but completions were <1%
- ⏳ Long program durations (>1 year) strongly correlated with dropouts
- 🧠 Early engagement is critical—delays between signup and start increase churn risk
- 📅 Highest signups occurred on Thursdays and Fridays
- 🧭 Personalized nudges and modular programs improve retention

The approach combined data cleaning, EDA, predictive modeling, and recommender system design to build a holistic retention strategy.

---

## 🧰 Tools & Technologies Used

| Category              | Tools/Technologies                          |
|-----------------------|---------------------------------------------|
| Data Processing       | Python (Pandas, NumPy), SQL                 |
| Visualization         | Power BI, Tableau                           |
| Modeling              | scikit-learn, Logistic Regression, Decision Trees, Random Forest |
| Recommendation System | Content-Based Filtering, Python, SQL       |

---

## 📌 Recommendations

- Use AI-driven alerts to flag at-risk learners early
- Break long programs into 30–60 day modules
- Automate reminders and mentor check-ins
- Tailor strategies by region and learner type
- Deploy real-time dashboards for retention tracking

---

## 🚀 Future Scope

- Integrate real-time behavioral data (clickstream, time-on-platform)
- Expand to hybrid recommendation models (content + collaborative)
- Scale across larger and more diverse datasets

---

> This project demonstrates how data science can transform education by predicting and preventing student dropouts. Let’s build smarter, more supportive learning ecosystems.
