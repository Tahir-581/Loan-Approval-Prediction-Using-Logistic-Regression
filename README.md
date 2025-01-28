# Loan Approval Prediction using Logistic Regression  

This project demonstrates a simple implementation of logistic regression to predict loan approval status based on applicant details. It includes data preprocessing, model training, prediction, and evaluation.

---

## Features  
The dataset contains the following features:  
- **ApplicantIncome**: Income of the applicant.  
- **CoapplicantIncome**: Income of the co-applicant.  
- **LoanAmount**: Amount of the loan requested.  
- **Loan_Term**: Term of the loan in months.  
- **Credit_History**: Credit history status (1: Good, 0: Bad).  
- **Education**: Education level (Graduate or Not Graduate).  
- **Self_Employed**: Employment type (Self-employed or Not).  
- **Loan_Status**: Loan approval status (Target variable).  

---

## Workflow  
1. **Data Loading**: Synthetic dataset creation.  
2. **Data Preprocessing**:  
   - Encoding categorical variables.  
   - Normalizing numerical features.  
3. **Train-Test Split**: Splitting data into training and test sets.  
4. **Model Training**: Training a logistic regression model.  
5. **Model Prediction**: Generating predictions on test data.  
6. **Evaluation**:  
   - Metrics: Accuracy, Precision, Recall, F1-Score.  
   - Confusion Matrix visualization.  
7. **Feature Importance Analysis**: Identifying significant features.  

---

## Key Results  
- Model Evaluation Metrics:  
  - **Accuracy**: Measures the overall correctness of the model.  
  - **Precision**: Measures the ratio of true positive predictions to all positive predictions.  
  - **Recall**: Measures the ratio of true positive predictions to actual positives.  
  - **F1-Score**: Harmonic mean of precision and recall.  

- **Confusion Matrix**: Visualizes correct and incorrect predictions.  

---

## Getting Started  

### Prerequisites  
- Python 3.8+  
- Libraries:  
  - `pandas`  
  - `numpy`  
  - `scikit-learn`  
  - `matplotlib`  

### How to Run  
1. Clone the repository.  
2. Install the required libraries using:  
   ```bash
   pip install -r requirements.txt
