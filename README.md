
# 🎯 Student Performance Prediction using Random Forest

Predicting student academic performance using a machine learning approach. This project leverages the **Random Forest Classifier** to analyze student data and predict academic outcomes based on various factors such as grades, lifestyle, and social background.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Machine Learning Pipeline](#machine-learning-pipeline)
- [How to Run](#how-to-run)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)
- [Contact](#contact)

---

## 📖 Project Overview

Academic performance prediction can help educators identify students who may need additional support. In this project, we build a Random Forest classification model to classify whether a student is likely to have a good or poor performance based on their demographic and academic features.

---

## 📊 Dataset Description

> Replace this with your own dataset description or link.

- **Source**: [Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Attributes**: Gender, Age, Study Time, Failures, Family Support, Internet Access, Absences, G1, G2, G3, etc.
- **Target Variable**: Final Grade or Performance Label (Pass / Fail)

---

## 🛠️ Technologies Used

- **Language**: Python
- **Environment**: Jupyter Notebook
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for machine learning and model evaluation

---

## 🧠 Machine Learning Pipeline

1. **Data Preprocessing**
   - Handling missing values
   - Label encoding categorical variables
   - Feature scaling (if needed)

2. **Feature Selection**
   - Correlation analysis
   - Feature importance from Random Forest

3. **Model Building**
   - Splitting dataset into train/test
   - Applying Random Forest Classifier
   - Hyperparameter tuning (optional)

4. **Evaluation**
   - Confusion Matrix
   - Classification Report
   - Accuracy, Precision, Recall, F1-Score

---

## 🚀 How to Run

### 🔧 Prerequisites

Install Python 3.12 and Jupyter Notebook.

### 💻 Clone this Repository

```bash
git clone https://github.com/yourusername/student-performance-rf.git
cd student-performance-rf
```
📦 Install Dependencies
```bash

pip install -r requirements.txt
```
### ▶️ Run the Notebook
```bash

jupyter notebook "Student Performance Prediction - Random Forest.ipynb"
```
## 📈 Model Evaluation
- Metric	Score
- Accuracy	0.87
- Precision	0.85
- Recall	0.88
- F1-Score	0.86

(Replace these values with your actual model results)

## ✅ Results
- The Random Forest model provided a strong accuracy score of ~87%, outperforming other basic models.

- Key influential features: G1, G2, studytime, failures, and absences.


## 📜 License
This project is licensed under the MIT License.

## 📬 Contact
Made with ❤️ by RAVINDRAN S
#### 🔗 [LinkedIn](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

