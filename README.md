# 🛡️ Network Intrusion Detection System (NIDS) using Machine Learning

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-SVM%20%7C%20NB%20%7C%20ANN-green)

## 📖 Project Overview
The **Artificial Intelligence (AI): Machine Learning Application for Detecting and Classifying Enterprise Network Intrusions** project focuses on researching and implementing Machine Learning / Deep Learning algorithms to build an automated, accurate, and efficient Intrusion Detection System (IDS).

Utilizing the standard **KDD Cup** dataset, the project involves training, evaluating, and comparing the performance of various models to identify anomalous behaviors and common cyberattack patterns targeting enterprise infrastructures.

---

## 🚀 Implemented Models

The project researches and evaluates the effectiveness of the following classification algorithms:
1. **Support Vector Machine (SVM)**: A robust machine learning model for linear and non-linear classification tasks.
2. **Naive Bayes (NB)**: A probabilistic algorithm based on Bayes' theorem, highly efficient for high-dimensional data processing.
3. **Artificial Neural Network (ANN)**: Artificial neural networks capable of capturing complex features from network packets.

---

## 📊 Dataset

The project utilizes the **KDD Cup** dataset (provided within the repository as `.csv` and `.gz` formats):
- `KDD_Train.csv` / `kddcup.data_5_percent.gz`: Training dataset.
- `KDD_Test.csv` / `kddcup.testdata.label_5_percent.gz`: Testing dataset.

The dataset features include information on TCP/IP connections, network traffic, and behavioral patterns of specific cyberattacks (such as DoS, R2L, U2R, and Probing).

---

## 📂 Repository Structure

- `IDS_SVM_NB.ipynb`: The main source code containing data preprocessing, model building, training, and evaluation for SVM and Naive Bayes models.
- `KDD_Train.csv`, `KDD_Test.csv`: The datasets used in this project.
- `BC_AI_CK_IT3_Khanh.doc`: Final term report document (Research Report).
- `*.png` (ModANN.png, SVM1.png,...): Visualizations, charts, and graphical results of the training processes and model accuracies.

---

## 📈 Visualizing Results

The system provides visual analysis via charts (available in the project directory):
- **Confusion Matrix** for each model.
- Performance comparisons (Accuracy, Precision, Recall, F1-Score) between SVM, NB, and ANN.
- Neural network feature representations as seen in `char_ANN.png` and `ModANN.png`.

---

## 🛠️ Installation & Usage Guide

1. **Clone the repository**:
   ```bash
   git clone https://github.com/phamquocan24/CMC_AI.git
   cd CMC_AI
   ```
2. **Install required libraries**:
   Using a virtual environment is recommended.
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter
   ```
3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   Open the `IDS_SVM_NB.ipynb` file and execute each code block to view the evaluation results.

---

## 📝 License
This project was developed for academic research purposes.
