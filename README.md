# Loan Approval Prediction: Machine Learning Project

This project demonstrates a complete **end-to-end machine learning pipeline** for predicting loan approval outcomes using structured financial data.  
It showcases **data cleaning, exploratory data analysis (EDA), feature engineering, and model training** with multiple algorithms, followed by a performance comparison to identify the most effective approach.

---

##  Project Overview
The financial services sector increasingly relies on data-driven decision-making.  
This project applies supervised learning techniques to classify whether a loan application should be **approved or declined**, based on customer demographics, financial metrics, and credit history.

---

##  Key Features
-  **Data Preprocessing**: Cleaned and transformed categorical and numerical data for model readiness.  
-  **Exploratory Data Analysis**: Identified trends, patterns, and relationships using visualisations.  
-  **Machine Learning Models**:
  - Support Vector Machine (SVM)
  - Decision Tree Classifier
  - Logistic Regression
  - K-Nearest Neighbours (KNN)
-  **Performance Metrics**:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrices for in-depth evaluation
-  **Results**: The **Decision Tree Classifier** achieved the highest accuracy (~97.7%), outperforming other models.

---

## Dataset
- Size: **4,269 records, 13 features**  
- Features include applicant income, loan amount, credit score, and asset values.  
- Target: `loan_status` (Approved / Not Approved)

---

##  Tech Stack
- **Languages**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Environment**: Google Colab

---

## Results Summary
| Model                  | Accuracy (%) |
|------------------------|-------------|
| Decision Tree          | **97.7**    |
| Logistic Regression    | 81.1        |
| SVM                    | 61.2        |
| KNN                    | 55.6        |

The **Decision Tree Classifier** shows exceptional performance, demonstrating its suitability for datasets with both categorical and numerical variables.

---

##  Key Takeaways
- End-to-end ML project demonstrating **practical data science skills**.  
- Highlights proficiency in **data preparation, visualisation, and model optimisation**.  
- Strong emphasis on **interpretable metrics** and real-world application relevance.

---

##  How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/YOUR_USERNAME/loan-approval-ml.git
