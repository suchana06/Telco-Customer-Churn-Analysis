# 📊 Telco Customer Churn Prediction  

## 🔥 Overview  
This project focuses on predicting customer churn in the telecom industry using **Machine Learning** techniques. The goal is to identify key factors influencing customer churn and develop a predictive model to assist businesses in customer retention strategies.  

The project follows a structured approach:  
- **Data Exploration & Preprocessing**  
- **Feature Engineering**  
- **Model Training & Evaluation**  
- **Hyperparameter Tuning**  
- **Model Selection**  
- **Dashboard Creation in Power BI**  

---

## 📁 Dataset  
The dataset consists of **7,043 rows and 21 columns**, where the target variable is **Churn (Yes/No)**. Key features include:  

- **Customer Information**: Customer ID, Gender, Senior Citizen, Partner, Dependents  
- **Service Details**: Phone Service, Multiple Lines, Internet Service, Streaming Services  
- **Billing & Contract**: Contract Type, Payment Method, Monthly Charges, Tenure  
- **Churn Label**: Indicates if the customer left (`Yes`) or stayed (`No`)  

---

## ⚙️ Tech Stack  
- **Programming Language**: Python 🐍  
- **Libraries Used**:  
  - Data Handling: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`  
  - Dashboarding: **Power BI**  

---

## 🚀 Data Preprocessing  
The dataset was cleaned and preprocessed using:  
- Handling missing values  
- Encoding categorical variables using **One-Hot Encoding**  
- Standardizing numerical features using **MinMaxScaler**  

---

## 🤖 Model Training & Evaluation  
Two machine learning models were implemented:  

| Model                 | Accuracy (Train) | Accuracy (Test) |
|-----------------------|----------------|----------------|
| **Logistic Regression** | **98.72%**         | **99%**         |
| Random Forest        | 98%             | 98%             |

### 🔧 Hyperparameter Tuning  
- **Logistic Regression**: Regularization (`C` parameter) was optimized using GridSearchCV.  
- **Random Forest**: Optimized `n_estimators`, `max_depth`, and `min_samples_split`.  

Finalized **Logistic Regression** as the best model based on accuracy and interpretability.  

---

## 📊 Power BI Dashboard  
A **Power BI Dashboard** was created to visualize key insights, including:  
- **Churn Rate Analysis**  
- **Customer Segmentation**  
- **Service & Contract Impact on Churn**  
- **Billing & Payment Behavior**  

---

## 🏆 Key Takeaways  
- **Tenure & Contract Type** strongly influence churn.  
- **Month-to-Month Contracts** show higher churn rates.  
- **Paperless Billing** customers are more likely to churn.  
- **Retention Strategies** can be optimized by targeting at-risk customers.  

---

## 📝 Future Improvements  
- Implement more advanced ML models like **XGBoost**.  
- Deploy the model using **Flask/FastAPI**.  
- Automate data updates in **Power BI**.  

---

## 📌 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/suchana06/Telco-Customer-Churn-Analysis.git

---

# ⭐ If you found this project useful, please give it a star! ⭐
