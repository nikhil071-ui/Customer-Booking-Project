# ✈️ Customer Booking Prediction Model

This project predicts whether a customer will complete their flight booking based on their past behavior and booking characteristics. It uses a machine learning pipeline with data preprocessing and a Random Forest classification model.

---

## 📂 Project Structure

---

## 🎯 Objective

To help airlines identify **which customers are more likely to complete a booking**, so they can:
- Improve targeted marketing
- Reduce booking drop-offs
- Personalize customer offers

---

## 🔧 Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python | Programming language |
| Pandas & Numpy | Data analysis & manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-Learn | Machine learning model & preprocessing |
| Jupyter Notebook | Model development environment |

---

## 🧹 Data Preprocessing
- Missing values handled
- Categorical values encoded (OneHotEncoder)
- Numeric values kept as-is
- Train-test split (80% training, 20% testing)

---

## 🤖 Model Used
**Random Forest Classifier**
- Handles mixed data types well
- Robust to overfitting
- Performs well with large datasets

---

## 📊 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | ~ 86% |
| Precision (Major Class) | 0.87 |
| Recall (Major Class) | 0.98 |
| F1-Score (Major Class) | 0.92 |

✨ The model predicts non-completed bookings well, but **recall for completed bookings is lower**, meaning more booking data or features like price sensitivity can improve accuracy.

---

## 🔍 Key Feature Insights
The **most influential features** affecting booking completion:
1. **purchase_lead** (Time between purchase & travel)
2. **flight_hour**
3. **length_of_stay**
4. **flight_duration**

Features like **wants_in_flight_meals** and **booking_origin** have lower importance.

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook final_model.ipynb
