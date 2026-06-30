# 🧠 Gen Z Mental Wellness & Digital Lifestyle Patterns

## 📌 Project Overview

Mental health challenges among Generation Z have become increasingly common. This project explores the relationship between digital lifestyle patterns (screen time, social media use, gaming, sleep habits, study/work balance) and mental wellness outcomes among Gen Z.
The goal is to build an end-to-end machine learning pipeline that predicts burnout risk and uncovers actionable insights into lifestyle-health connections.

---

## 🎯 Objectives

- Predict burnout risk (Low, Medium, High) from digital lifestyle features.
- Identify hidden lifestyle clusters (e.g., "night owls," "heavy gamers," "social media
  influencers").
- Provide interpretable insights into how digital habits affect wellbeing.
- Deploy results in an interactive dashboard for portfolio-ready presentation.

---

## 📂 Project Structure

* data- Raw & processed datasets
* notebooks- Guided Jupyter notebooks with annotations
* src- Core ML pipeline scripts
* dashboard- Streamlit app for interactive visualization
* README.md- Project documentation
* requirements.txt- Dependencies


---

## ⚙️ Workflow
1. Data Collection
   - Surveys, Kaggle datasets, public health sources.
   - Features: screen time, sleep patterns, social media use, study/work balance, stress levels.

2. Preprocessing
   - Cleaning, encoding categorical variables, scaling numeric features.
   - Feature engineering (e.g., productive vs. entertainment screen time ratio).

3. Exploratory Data Analysis (EDA)
   - Correlation heatmaps.
   - Lifestyle clustering.
   - Burnout risk distribution.
4. Modeling
   - Supervised: Random Forest, Gradient Boosting.
   - Unsupervised: K-means, DBSCAN, PCA.
   - NLP: Sentiment/emotion detection from text data.
5. Evaluation
   - Metrics: Accuracy, F1-score, RMSE.
   - Confusion matrix for class-level performance.
   
  6. Interpretability
     - Feature importance plots.
     - SHAP values, permutation importance, partial dependence plots.

7. Deployment
   * Streamlit dashboard with tabs for:
     - EDA
     - Model Results
     - Persona Clusters

---

## 📊 Dashboard Highlights
- Burnout Risk Predictions: Interactive classification results.
- Lifestyle Personas: Clustered groups with descriptive labels.
- Feature Insights: Visual explanations of model decisions.

---

## 🛠️ Tech Stack
- Python: pandas, NumPy, scikit-learn, seaborn, matplotlib
- Visualization: Streamlit, Plotly
- Interpretability: SHAP, permutation importance
- Deployment: Streamlit dashboard


---

## 📷 Project Screenshots

Add screenshots such as:

- Correlation Heatmap
- Feature Importance
- Confusion Matrix
- ROC Curve
- Model Accuracy Comparison

Example:

![Correlation Heatmap](images/heatmap.png)

---

## 🚀 How to Run the Project

Clone the repository

```bash
git clone https://github.com/yourusername/genz-mental-health-ml.git
```

Navigate into the project

```bash
cd genz-mental-health-ml
```

Install the required packages

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
GenZ_Mental_Health.ipynb
```

---

## 📁 Project Structure

```
genz-mental-health-ml/
│
├── data/
├── notebooks/
├── images/
├── models/
├── requirements.txt
├── README.md
└── GenZ_Mental_Health.ipynb
```

---

## 📌 Key Findings

- Sleep quality strongly influences mental health.
- Financial stress contributes significantly to anxiety.
- Academic pressure is one of the strongest predictors.
- Random Forest achieved the highest prediction accuracy.

*(Update these findings to reflect your own analysis.)*

---

## 👤 Author

**Allan Ngigi**

Economics & Statistics Graduate

Python | SQL | Power BI | Machine Learning

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile
