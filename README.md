# Data-Science-in-Cybersecurity-Final-Project

# Phishing Website Detection using Machine Learning Techniques

## Student Information

**Name:** Saada Sabek

**Student ID:** 213703663

**Course:** Data Science Methods in Cybersecurity

---

# Project Description

The objective of this project is to reproduce and critically evaluate a machine learning solution for phishing website detection. The project investigates how supervised machine learning algorithms can distinguish phishing websites from legitimate websites using engineered cybersecurity features extracted from URLs and domain characteristics.

Several machine learning models were trained, evaluated, and compared in order to reproduce the original study and assess its methodology and conclusions.

---

# Machine Learning Models

The following machine learning models were evaluated:

* Decision Tree
* Random Forest
* Multilayer Perceptron (MLP)
* XGBoost
* Support Vector Machine (SVM)

The models were evaluated using the following performance metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Matthews Correlation Coefficient (MCC)
* Confusion Matrix

---

# Original Project

Original GitHub Repository:

https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques

---

# Dataset

The phishing website dataset used in this project is the same dataset provided in the original repository.

Dataset source:

https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques

The dataset contains **10,000 website samples** described by **17 engineered cybersecurity features** and one target variable (Label), indicating whether the website is phishing or legitimate.

---

# Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install all required Python packages:

```bash
pip install -r requirements.txt
```

Open the notebook using **Jupyter Notebook** or **Google Colab**, then run all cells from top to bottom.

---

# Final Results

All evaluated machine learning models achieved good classification performance.

The best-performing model in our implementation was the **Multilayer Perceptron (MLP)** with an accuracy of approximately **87.2%**, followed closely by **XGBoost** with approximately **87.0%**.

Although the original notebook reported XGBoost as the best-performing model, our reproduction achieved slightly better performance with MLP. The difference between the two models was very small and did not change the overall conclusions of the study.

---

# Critical Findings

The reproduction study confirmed the main claims presented in the original project.

The experiments demonstrated that:

* Feature engineering plays a major role in phishing website detection.
* Multiple evaluation metrics provide a more reliable assessment than accuracy alone.
* Machine learning models can effectively distinguish phishing websites from legitimate websites.
* The project is reproducible and suitable as a baseline for similar cybersecurity problems.

---

# Repository Contents

* `Copy_of_Phishing_Website_Detection_Models_&_Training.ipynb` – Complete notebook containing data analysis, model training, and evaluation.
* `ProjectReport.pdf` – Final project report.
* `requirements.txt` – Required Python libraries.
* `5.urldata.csv` – Dataset used in this project.
* `README.md` – Project overview and execution instructions.

---

# References

* Original GitHub Repository:
  https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques

* Dataset:
  https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques

