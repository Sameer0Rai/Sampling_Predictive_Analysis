# 📊 Sampling Techniques for Imbalanced Credit Card Dataset  

**Course:** UCS654 – Predictive Analytics using Statistics  
**Assignment:** Sampling Techniques  
**Student Name:** Sameer Rai  
**Roll Number:** 102303773  

---

## 📌 Introduction  

In real-world machine learning applications, datasets are often **imbalanced**, where one class significantly outnumbers the other. This imbalance can negatively impact model performance, particularly when the minority class represents critical outcomes such as fraud detection.

This project applies multiple **sampling techniques** to balance a credit card fraud dataset and evaluates their impact on different classification algorithms.

---

## 🎯 Objectives  

- Analyze the impact of class imbalance on ML models  
- Apply different sampling techniques  
- Compare model performance using suitable evaluation metrics  
- Demonstrate why accuracy alone is insufficient for imbalanced datasets  

---

## 🗂 Dataset Description  

- Dataset: Credit Card Transaction Data  
- Problem Type: Binary Classification (**Fraud vs Non-Fraud**)  
- Dataset Nature: Highly imbalanced  
- Application: Fraud Detection  

---

## ⚙️ Sampling Techniques Used  

1. **Random Under-Sampling**  
2. **Random Over-Sampling**  
3. **SMOTE (Synthetic Minority Over-sampling Technique)**  

---

## 🤖 Machine Learning Models Implemented  

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Gaussian Naive Bayes  

---

## 📊 Evaluation Metrics  

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC Score  

---

## 📁 Repository Structure  
```
Sampling-Predictive-Analysis/
│
├── Creditcard_data.csv # Original dataset
├── Sampling.ipynb # Complete implementation (data preprocessing, sampling, model training)
├── result_sampling.csv # Final comparison results of all models & sampling techniques
├── requirements.txt # Project dependencies
├── README.md # Project documentation
```

---

## ▶️ How to Run the Project  

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Sameer0Rai/Sampling_Predictive_Analysis
```
### 2️⃣ Navigate to Project Directory

After cloning the repository, move into the project folder:

```bash
cd Sampling-Techniques-CreditCard
```
> Replace `Sampling-Techniques-CreditCard` with your actual repository name if different.

---

### 3️⃣ Install Required Dependencies

Install all necessary Python libraries using:

```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Jupyter Notebook

Launch Jupyter Notebook using:

```bash
jupyter notebook Sampling.ipynb
```
---
## 📈 Results Summary  

- Class imbalance significantly affects fraud detection performance.  
- Sampling techniques improve minority class prediction.  
- Precision, Recall, F1-Score, and ROC-AUC provide better evaluation than accuracy alone.  
- SMOTE generally improves recall for fraudulent transactions.  

---

## ✅ Conclusion  

This project demonstrates the importance of handling imbalanced datasets in classification tasks. By applying appropriate sampling strategies and evaluating models using meaningful metrics, more reliable and effective fraud detection systems can be developed.

