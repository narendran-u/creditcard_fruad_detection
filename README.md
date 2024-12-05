
---

# 💳 Credit Card Fraud Detection

## 🚀 Overview

The **Credit Card Fraud Detection** project is designed to identify fraudulent transactions using advanced machine learning and deep learning techniques. The dataset, sourced from Kaggle, is highly **imbalanced**, with only 0.17% of transactions classified as fraudulent. ⚠️ This project employs strategies to address the imbalance and ensure robust fraud detection. 🛡️

---

## ✨ Features

- 🔄 **Data Preprocessing**: Cleaning and transforming the dataset for analysis.  
- 🧠 **Machine Learning & Deep Learning**: Implementation of both shallow models and a neural network using Keras.  
- 📊 **Imbalanced Data Handling**: Using techniques like SMOTE and evaluation metrics that consider class imbalance.  
- 🔍 **Feature Insights**: Analysis of the key factors affecting fraud detection.  

---

## 📂 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Description**:  
  - Contains 284,807 transactions made by credit cards in September 2013.  
  - **Fraudulent Transactions**: Only 492 (~0.17%).  
  - **Challenge**: Extreme class imbalance requiring special handling techniques.  

---

## 🛠️ Technologies Used

- Python 🐍  
- Pandas & NumPy for data manipulation 📊  
- Scikit-learn for machine learning ⚙️  
- Matplotlib & Seaborn for data visualization 📈  
- **Keras (with TensorFlow backend)** for deep learning 🧠  

---

## 🤖 Algorithms Used

1. **Logistic Regression** 📈  
2. **Random Forest Classifier** 🌲  
3. **Gradient Boosting (XGBoost)** 🚀  
4. **Shallow Neural Network** built with **Keras** 🧠  

### Addressing Imbalance:
- **Techniques Used**:  
  - SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.  
  - Cost-sensitive learning by adjusting class weights in Keras models.  
- **Evaluation Metrics**: Precision, Recall, F1-score, and ROC-AUC.  

---

## ⚙️ Setup

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the project:  
   ```bash
   jupyter notebook fraud_detection.ipynb
   ```

---

## 📊 Results



- **Logistic Regression**:  
  - Reliable baseline performance.  
- **Random Forest**:  
  - Strong interpretability and balanced metrics.  
- **Gradient Boosting**:  
  - Best performance in terms of ROC-AUC and F1-score.  
- **Shallow Neural Network (Keras)**:  
  - Superior results when properly tuned with cost-sensitive learning.  

---

## 🔍 Usage

1. Load the Kaggle dataset and preprocess it.  
2. Train the machine learning models (Logistic Regression, Random Forest, Gradient Boost).  
3. Build and train the shallow neural network using Keras.  
4. Evaluate the models using metrics suited for imbalanced data.  
5. Predict fraud on new transaction data.  

---

## 🤝 Contributing

Contributions are welcome! Fork this repository, raise issues, or submit pull requests. 💡

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).  

---

