# 🤖 Impact of ChatGPT on Students – ML Survey Analysis

This project explores the **impact of ChatGPT on students** using survey data collected via **Google Forms**. After cleaning and visualizing the data, machine learning classification models are trained to predict whether a student relies more on AI tools after using ChatGPT.

---

## 📋 Project Overview

- 📌 Collected **500+ student responses** via Google Forms  
- 📌 Cleaned and preprocessed survey data  
- 📌 Created age groups and handled categorical responses  
- 📌 Performed **exploratory data analysis** using visualizations  
- 📌 Trained two ML models: **Random Forest** and **Naive Bayes**  
- 📌 Evaluated models using Accuracy, Classification Report, and **Confusion Matrix**

---

## 🧠 Models Used

| Model         | Description                                 |
|---------------|---------------------------------------------|
| Naive Bayes   | Probabilistic classifier (CategoricalNB)    |
| Random Forest | Ensemble model using decision trees         |

---

## 📁 Dataset

The dataset `Completed_Survey_500_Responses.csv` includes the following features:

- Age & Age Group  
- Gender  
- Academic Level  
- ChatGPT Usage Frequency  
- Weekly Time Spent on ChatGPT  
- Perceived Benefits & Drawbacks  
- **Target Variable:** _"Do you find yourself relying more on AI tools since using ChatGPT?"_

> Data was collected via Google Forms and exported to CSV format.

---

## 📊 Visualizations Included

✅ Age Group Distribution  
✅ ChatGPT Usage Frequency  
✅ AI Tool Reliance by Age Group  
✅ Boxplot: Time Spent on ChatGPT vs Age Group  
✅ Heatmap: ChatGPT Usage vs AI Tool Reliance  
✅ Confusion Matrices for Models

_All visualizations are created using `seaborn` and `matplotlib`._

---

## 🔍 Model Evaluation

### 🎯 Metrics Reported
- Accuracy  
- Precision, Recall, F1-score (via Classification Report)  
- Confusion Matrix

### 📌 Sample Results

#### ✅ Random Forest
- Accuracy: **86.00%**
- Balanced precision/recall
- Clear prediction boundaries

#### ✅ Naive Bayes
- Accuracy: **78.67%**
- Good performance on categorical survey data

---

## 📂 Project Structure

ChatGPT-Impact-Analysis/
├── Completed_Survey_500_Responses.csv
├── chatgpt_analysis.ipynb
├── images/
│ ├── age_distribution.png
│ ├── heatmap_usage_vs_ai.png
│ ├── confusion_matrix_rf.png
│ └── confusion_matrix_nb.png
└── README.md



---

## ⚙️ How to Use

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ChatGPT-Impact-Analysis.git
cd ChatGPT-Impact-Analysis
```
### 2. Install the dependencies

pip install -r requirements.txt

or insall manually:
like: pip install pandas matplotlib seaborn scikit-learn

