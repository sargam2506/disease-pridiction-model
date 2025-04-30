# 🧠 Disease Prediction System using Machine Learning

This project is a **Disease Prediction Web Application** developed using **Python** and trained with machine learning algorithms such as **Random Forest**, **Naive Bayes**, and **Decision Tree**. The system takes user-input symptoms and predicts the most probable disease based on trained data.

---

## 🚀 Features

- 🔍 Predicts disease based on **any 3 to 5 symptoms** entered by the user.
- 🤖 Uses **3 different ML algorithms** for prediction:
  - Random Forest
  - Naive Bayes
  - Decision Tree
- 💡 Interactive frontend with:
  - **Spinner animation** during prediction
  - **Hover effect** on prediction buttons
  - **Warning message** if fewer than 3 symptoms are selected
- 🔒 User must **enter their name** before proceeding to prediction.
- 🧾 Easy-to-use dropdown menus for selecting symptoms.
- ✅ Results displayed clearly based on selected algorithm.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask or Streamlit, if used)
- **Machine Learning**: scikit-learn (RandomForest, DecisionTree, NaiveBayes)
- **Libraries**: pandas, numpy, sklearn, joblib (for model persistence)

---

## 📊 Machine Learning Models

All three models were trained on a labeled disease dataset consisting of symptoms mapped to corresponding diseases.

| Algorithm      | Strength                              | Use Case                            |
|----------------|----------------------------------------|-------------------------------------|
| Random Forest  | High accuracy, low overfitting         | Best for general prediction         |
| Decision Tree  | Easy to interpret                      | Suitable when transparency is needed|
| Naive Bayes    | Fast and lightweight                   | Ideal for mobile or fast prediction |


---

## ⚙️ How to Run the Project Locally

1. **Clone the repository**
```bash
https://github.com/sargam2506/disease-pridiction-model.git
