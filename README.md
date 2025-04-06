# Logistic Regression 

A binary classification project using logistic regression

## 📦 Features
- Logistic regression with hyperparameter tuning (GridSearchCV & RandomizedSearchCV)
- Evaluation with accuracy, precision, recall, F1-score, and confusion matrix
- Well-structured code and notebook
- Git-tracked with a clean `.gitignore`

## 📊 Dataset
Simulated dataset representing binary outcomes (0 = no crash, 1 = crash).

## ⚙️ Model Tuning
- Grid Search & Randomized Search across:
  - `solver`: liblinear, saga, newton-cg, etc.
  - `penalty`: l1, l2, elasticnet
  - `C`: Regularization strength

## ✅ Performance
- Cross-Validation Score: **~95.4%**
- Test Accuracy: **93%**
- Balanced precision & recall

## 🛠️ To Run
1. Clone this repo  
2. Install dependencies from `requirements.txt`  
3. Run the notebook or script
