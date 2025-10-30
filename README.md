# -Loan-Approval-Prediction-Using-Random-Forest
Predicting loan approval outcomes using machine learning. This project utilizes a Random Forest model to analyze financial and applicant data, achieving an accuracy rate of 76%. Visual analyses highlight credit history and income as the strongest predictors influencing loan approval decisions.

## 📘 Project Overview  
This project predicts loan approval outcomes using applicant financial and personal information.  
The goal is to help financial institutions make data-driven loan decisions efficiently and fairly.  

The analysis was performed using Python and Scikit-learn’s Random Forest Classifier, achieving about **76% accuracy**.  
Key steps included cleaning data, handling missing values, encoding categorical variables, and building machine learning models.  

---

## ⚙️ Data Preparation  
- Loaded dataset from Kaggle.  
- Cleaned missing values using median and mode imputation.  
- Encoded categorical columns (Gender, Education, etc.) into numeric values.  
- Converted “3+” in *Dependents* to integer 3.  
- Split the dataset into training (80%) and testing (20%) sets.  

---

## 🤖 Model & Evaluation  
**Algorithm Used:** RandomForestClassifier  
- Accuracy: **75.6%**  
- Strong at predicting approved loans (high recall).  
- Slightly weaker for rejected loans (can be improved by balancing data).  

---

## 📊 Visual Insights  

### 🔹 Confusion Matrix  
- Shows 75 correct approvals and 18 correct rejections.  
- Model predicts most approved cases correctly but misses a few rejections.  

### 🔹 Feature Importance  
Top 3 factors influencing loan approval:  
1. **Credit_History**  
2. **ApplicantIncome**  
3. **LoanAmount**  

These indicate that applicants with strong credit history and higher income are more likely to get loan approval.  

---

## 💡 Key Takeaways  
- Credit history and income are the most influential predictors.  
- The model can serve as a **baseline** for automating loan eligibility screening.  
- Further optimization can include hyperparameter tuning or logistic regression comparisons.  

---

## 🧩 Tools Used  
`Python | Pandas | NumPy | Seaborn | Matplotlib | Scikit-learn`

---

## 🏁 Next Steps  
- Add SHAP or LIME visualizations for model explainability.  
- Build a Streamlit app to deploy the predictor online.  
- Experiment with ensemble and boosting models for higher accuracy.

---

## ✨ Summary  
This project demonstrates how **AI can streamline loan decision-making**, revealing the most critical factors that influence approvals.  
The Random Forest model provides a strong baseline for further development into a production-ready financial AI solution.
  

