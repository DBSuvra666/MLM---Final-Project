
# 🌟 Supervised Learning Models on Import-Export Dataset 🌟

### 📄 **Project Overview**
This project demonstrates the application of **Supervised Machine Learning Models** to classify and analyze an import-export dataset. By leveraging Python libraries such as **Pandas**, **NumPy**, and popular ML frameworks, the project explores data preprocessing, visualization, model building, and performance evaluation. 

---

## 🗂️ **Contents**
- Project Information
- Description of Data
- Project Objectives
- Exploratory Data Analysis
- Machine Learning Models
- Performance Metrics
- Key Observations

---

## 📌 **Project Information**
- **Title:** Supervised Learning Models on Import-Export Dataset
- **Prepared By:** [Add Your Name and Roll Number]
- **Tools Used:** Python (Jupyter Notebook), Scikit-learn, Matplotlib, Seaborn, XGBoost

---

## 📊 **Description of Data**
- **Data Source:** Import-Export Dataset (source not provided in file)
- **Key Variables:**
  - **Numerical:** Quantity, Value, Weight
  - **Categorical:** Country, Product, Port, Shipping Method, etc.
  - **Datetime:** Transaction date
- **Sample Size:** 5001 entries extracted from a larger dataset.

---

## 🎯 **Project Objectives**
- Classify the dataset into meaningful clusters or categories using supervised learning models.
- Identify significant features contributing to classification.
- Evaluate and compare the performance of multiple ML models based on key metrics.

---

## 🔍 **Exploratory Data Analysis**
- **Preprocessing:**
  - No missing values were detected.
  - Data was encoded using **Ordinal Encoder** and scaled using **Min-Max Scaling**.
- **Visualization:**
  - Bar charts, heatmaps, histograms, and correlation matrices were used to explore patterns.
- **Descriptive Statistics:**
  - Measures like Mean, Median, Standard Deviation, and Skewness were calculated.

---

## 🤖 **Machine Learning Models**
The following supervised learning models were applied and evaluated:
- Logistic Regression
- Support Vector Machine (SVM)
- Stochastic Gradient Descent (SGD)
- Decision Tree
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Random Forest
- XGBoost

### **Model Performance Metrics**
- Confusion Matrix: Sensitivity, Precision, Recall, and F1-score.
- Cross-Validation: Evaluated model robustness using K-Fold CV.
- Runtime and Memory: Compared computational efficiency across models.

---

## 📈 **Performance Metrics**
| **Model**           | **Accuracy (Test Set)** | **Mean CV Accuracy** | **Runtime (seconds)** | **Memory Usage (MB)** |
|----------------------|-------------------------|-----------------------|------------------------|-----------------------|
| Logistic Regression  | 0.3158                 | 0.3503                | 0.0418                | 0.34                 |
| SVM                  | 0.3251                 | 0.3537                | 2.0424                | 0.38                 |
| SGD                  | 0.3158                 | 0.3503                | 0.1159                | 0.31                 |
| Decision Tree        | 0.3238                 | 0.3331                | 0.0558                | 0.27                 |
| KNN                  | 0.3200                 | 0.3258                | 0.0011                | 0.38                 |
| Naive Bayes          | 0.3171                 | 0.3171                | 0.0045                | 0.11                 |
| Random Forest        | 0.3331                 | 0.3498                | 2.0525                | 0.54                 |
| XGBoost              | 0.3298                 | 0.3529                | 1.1805                | 1.02                 |

---

## 📝 **Key Observations**
1. **Best Accuracy:** Random Forest and XGBoost demonstrated the highest accuracy scores.
2. **Fastest Model:** KNN was the fastest to run (0.0011 seconds), followed by Naive Bayes.
3. **Most Memory Efficient:** Naive Bayes had the lowest memory usage (0.11 MB), while XGBoost consumed the most (1.02 MB).
4. **Balanced Performance:** Logistic Regression and SVM showed consistent performance across metrics, while Naive Bayes and KNN exhibited lower accuracies.


---

## 📬 **Contact**
For questions or collaboration, feel free to reach out:
- **Email:** dattabaniksuvra@gmail.com
- **LinkedIn:** www.linkedin.com/in/suvra-datta-banik-240b90156

---

🌟 **Thank you for exploring this project! Contributions and feedback are always welcome.** 🌟
