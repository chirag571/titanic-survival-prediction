Machine Learning project using Logistic Regression for Titanic survival prediction.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chirag571/titanic-survival-prediction/blob/main/Titanic_Survival_Prediction.ipynb)

# 🚢 Titanic Survival Prediction

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning techniques. It demonstrates the complete data science workflow including data preprocessing, visualization, feature engineering, and model building.

---

## 🎯 Objective

* Analyze Titanic dataset
* Perform data visualization
* Build a machine learning model for survival prediction
* Evaluate model performance

---

## 📂 Dataset

The dataset used in this project is the Titanic dataset, which contains information about passengers such as age, gender, passenger class, fare, and survival status.

🔗 **Dataset Link:** https://www.kaggle.com/c/titanic/data

The dataset was accessed directly using the Seaborn library in Python:

```python
import seaborn as sns
df = sns.load_dataset('titanic')
```

For reference, the dataset is also available in CSV format on Kaggle.


---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔍 Steps Performed

1. Data Cleaning (handling missing values)
2. Data Visualization (bar plots, heatmaps)
3. Feature Engineering (created FamilySize)
4. Model Building using Logistic Regression
5. Model Evaluation using Accuracy and Confusion Matrix

---

## 📊 Model Performance

* **Model Used:** Logistic Regression
* **Accuracy:** 80.44%

### 📉 Confusion Matrix

```
[[92 13]
 [22 52]]
```

---

## 📸 Results

### Survival Count

![Survival Count](screenshots/survival_count.png)

### Survival by Gender

![Gender Survival](screenshots/gender_survival.png)

### Heatmap

![Heatmap](screenshots/heatmap.png)

### Confusion Matrix

![Confusion Matrix](screenshots/confusion_matrix.png)

---

## 📁 Project Structure

```
titanic-survival-prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── Titanic_Report.pdf
├── data/
│   └── train.csv
├── screenshots/
│   ├── survival_count.png
│   ├── gender_survival.png
│   ├── heatmap.png
│   └── confusion_matrix.png
└── README.md
```

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook
2. Run all cells step-by-step
3. View results and graphs

---

## 📌 Conclusion

The Logistic Regression model achieved good accuracy and demonstrated that machine learning can effectively solve classification problems like survival prediction.

---

## 🔗 Author

Chirag Negi
