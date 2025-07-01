# 📘 Data Science Lectures with Python

This repository contains a complete series of lectures focused on **Data Science and Machine Learning** using Python. Each lecture covers both **theoretical concepts** and **hands-on implementation** using real-world datasets. Designed for students and beginners, this series provides weekly learning materials, coding tasks, and project-based learning opportunities.

---

## 📋 Lecture List & Status

| No. | Lecture Title       | Status        |
| --- | ------------------- | ------------- |
| 01  | Linear Regression   | ✅ Completed   |
| 02  | Logistic Regression | ✅ Completed   |
| 03  | Support Vector Machine (SVM) | ✅ Completed   |
| 04  | Decision Tree       | ⏳ Coming Soon |
| 05  | Random Forest       | ⏳ Coming Soon |

---

## 📦 Installation Requirements

To run the notebooks in this repository, make sure the following packages are installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Or use the `requirements.txt` (coming soon):

```bash
pip install -r requirements.txt
```

---

## 📥 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Data-Science-Lectures-with-Python.git
   ```

2. Navigate to a lecture folder (e.g., SVM):

   ```bash
   cd Data-Science-Lectures-with-Python/03_SVM
   ```

3. Open the notebook:

   ```bash
   jupyter notebook SVM_Lecture_Detailed.ipynb
   ```

---

## 📚 Topics Covered

### ✅ Linear Regression Lecture
* Simple vs. Multiple Linear Regression
* Cost Function (MSE)
* Model Training & Evaluation (R², RMSE)
* Data Visualization & Residual Analysis

### ✅ Logistic Regression Lecture
* Binary Classification & Sigmoid Function
* Cross-Entropy Loss & Gradient Descent
* Regularization (L1, L2)
* Confusion Matrix, Precision, Recall, F1-Score
* ROC Curve & AUC
* Model Interpretation with Coefficients
* Hands-on: Breast Cancer Dataset

### ✅ Support Vector Machines (SVM) Lecture
* Linear vs. Non-Linear Classification
* Margin Maximization & Hyperplane
* Soft Margin and Regularization (C)
* Kernels: Linear, Polynomial, RBF
* Hyperparameter Tuning (GridSearchCV)
* Hands-on: Breast Cancer Dataset

---

## 📃 Tasks for Students

### Linear Regression Task
* Select a regression dataset (e.g., house prices)
* Apply linear regression and evaluate performance
* Visualize results and explain findings

### Logistic Regression Task
* Choose a binary classification dataset (e.g., Titanic, Pima Diabetes)
* Perform EDA, preprocess, and train logistic regression model
* Evaluate using classification metrics & ROC Curve
* Interpret model coefficients

### SVM Task
* Use a binary classification dataset (e.g., Heart Disease)
* Compare linear vs. RBF SVM models
* Apply GridSearchCV for hyperparameter tuning
* Evaluate with confusion matrix, precision, recall, F1-score

📄 **Submit your Jupyter Notebook on GitHub with proper documentation**

---

## 🙌 Contribution Guidelines (Optional)

If you'd like to contribute additional lectures or improvements, feel free to fork the repo and create a pull request. Contributions are welcome!

---

## 🧱 Folder Structure

```
Data-Science-Lectures-with-Python/
│
├── 01_Linear_Regression/
│   ├── Linear_Regression_Lecture.ipynb
│   ├── Linear_Regression_Lecture.pdf
│   ├── Task_Instructions.txt
│   └── dataset/
│       └── diabetes.csv
│
├── 02_Logistic_Regression/
│   ├── Logistic_Regression_Lecture.ipynb
│   ├── Logistic_Regression_Lecture.pdf
│   ├── Task_Instructions.txt
│   └── dataset/
│       └── breast_cancer.csv
│
├── 03_SVM/
│   ├── SVM_Lecture_Detailed.ipynb
│   ├── SVM_Lecture_Detailed.pdf
│   ├── Task_Instructions.txt
│   └── dataset/
│       └── heart_disease.csv
│
└── README.md
```
