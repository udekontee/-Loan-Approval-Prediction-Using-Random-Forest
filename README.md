# Loan-Approval-Prediction-Using-Random-Forest
Predicting loan approval outcomes using machine learning.  
This project utilizes a **Random Forest Classifier** to analyze financial and applicant data, achieving an accuracy rate of **76%**.  
Visual analyses highlight **credit history** and **income** as the strongest predictors influencing loan approval decisions.

---

## 📘 Project Overview
This project predicts loan approval outcomes using applicant financial and personal information.  
The goal is to help financial institutions make **data-driven loan decisions** efficiently and fairly.  

The analysis was performed using **Python** and **Scikit-learn’s Random Forest Classifier**, achieving about **76% accuracy**.  
Key steps included **data cleaning, handling missing values, encoding categorical variables**, and **building and evaluating machine learning models**.

---

## ⚙️ Data Preparation
- Loaded dataset from **Kaggle**.  
- Cleaned missing values using **median and mode imputation**.  
- Encoded categorical columns (Gender, Education, Self_Employed, etc.) into numeric values.  
- Converted “3+” in *Dependents* to integer `3`.  
- Split the dataset into **training (80%)** and **testing (20%)** sets.  

---

## 🤖 Model & Evaluation
**Algorithm Used:** RandomForestClassifier  

| Metric | Result |
|--------|---------|
| Accuracy | **75.6%** |
| Precision | Good on “Approved” class |
| Recall | High for “Approved,” lower for “Rejected” |
| Dataset Split | 80% Train / 20% Test |

**Observations:**  
- The model performs strongly for predicting **approved loans**, indicating robust pattern recognition in credit-related variables.  
- Slight class imbalance affects rejected cases — can be improved with re-sampling or cost-sensitive modeling.

---

## 📊 Visual Insights

### 🔹 Confusion Matrix
- 75 correct approvals and 18 correct rejections.  
- Most approved loans are predicted accurately; slight bias toward approval due to dataset imbalance.  

### 🔹 Feature Importance
Top 3 factors influencing loan approval:
1. **Credit_History**  
2. **ApplicantIncome**  
3. **LoanAmount**  

These insights show that applicants with solid credit history and higher income are **statistically more likely** to be approved — confirming financial decision logic used in banking and lending sectors.

---

## 💼 Business Relevance
This project simulates a **predictive financial risk model**, similar to the ones used in the **automotive finance** and **banking industries** to assess applicant creditworthiness and predict loan repayment likelihood.  
It mirrors how organizations like **Ford Credit** or other financial divisions analyze **historical data, income stability, and credit behavior** to forecast approval decisions and minimize default risk.  

By applying a Random Forest algorithm, this project demonstrates how **machine learning can automate and standardize loan evaluation**, leading to more consistent, transparent, and data-driven lending practices.  
The modeling process also parallels **residual value forecasting** and **economic risk modeling**, where financial inputs predict outcomes like price depreciation or default probability.

---

## 💡 Key Takeaways
- **Credit history** and **income** are the strongest predictors of loan approval.  
- The model can serve as a **baseline AI system** for automating loan eligibility screening.  
- **Hyperparameter tuning** and **data balancing** can enhance performance and fairness.  
- Laying the groundwork for future **model deployment** in financial decision workflows.

---

## 🧩 Tools Used
`Python | Pandas | NumPy | Seaborn | Matplotlib | Scikit-learn`

---

## 🏁 Next Steps
- Add **SHAP or LIME** visualizations for explainability and bias detection.  
- Deploy the model using **Flask or Streamlit** for real-time predictions.  
- Integrate **ensemble and boosting models** for improved predictive accuracy.  
- Explore **AWS SageMaker** for cloud-based training and deployment.  

---

## ✨ Summary
This project demonstrates how **machine learning can transform financial decision-making**, improving accuracy, efficiency, and fairness in loan approvals.  
The Random Forest model provides a **strong foundation for financial forecasting**, model interpretability, and real-world deployment in automated credit systems.

---

👩🏽‍💻 **Author:** U Dekontee Kun  
📬 **Email:** udekontee@gmail.com  
🔗 **Portfolio:** [github.com/udekontee](https://github.com/udekontee)
