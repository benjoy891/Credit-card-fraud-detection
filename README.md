# 💳 Credit Card Fraud Detection

This project uses machine learning techniques to detect fraudulent credit card transactions. It aims to help financial institutions identify suspicious activities with high accuracy while minimizing false positives.

---

## 📁 Project Structure


---

## 🧠 Objective

The goal of this project is to develop a model that can distinguish between legitimate and fraudulent transactions using historical credit card approval data.

---

## 📊 Dataset

- **Source**: [UCI Credit Card Approval Dataset](https://archive.ics.uci.edu/ml/datasets/Credit+Approval)
- **File**: `cc_approvals.data`
- **Features**: Contains various anonymized features related to transactions and customer profiles.
- **Target**: Whether a credit card application is approved or not (1 = Approved, 0 = Rejected)

---

## ⚙️ Technologies Used

- Python 3.x
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🔍 Workflow

1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize numeric values  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize class distribution  
   - Correlation analysis  

3. **Modeling**  
   - Train/test split  
   - Logistic Regression  
   - Random Forest  
   - Evaluation using accuracy, precision, recall, F1-score

4. **Conclusion**  
   - Best-performing model selection  
   - Insights and recommendations  

---

## 📈 Results

- Achieved high precision in detecting fraudulent applications.
- Random Forest showed the best performance based on F1-score.

---

## 📷 Visualization

![Credit Card](credit_card.jpg)

---

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/credit-fraud-detection.git
   cd credit-fraud-detection
