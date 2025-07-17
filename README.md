# Feature Forge: Enhancing & Evaluating ML Models

This project focuses on improving, validating, and evaluating machine learning models using a real-world classification problem — predicting loan approval status.

The notebook walks through various model enhancement techniques, stress testing, and performance evaluations to ensure a robust and reliable ML pipeline.

---

##  Project Structure

This project is divided into 3 milestones:

### Milestone 1: Feature Engineering
- Performed data cleaning and preprocessing
- Feature selection and transformation
- Handled missing values, encoding, and scaling

### Milestone 2: Model Enhancement & Tuning

####  Task 1: Hyperparameter Tuning
- Tuned hyperparameters (`C` and `solver`) for Logistic Regression using `GridSearchCV`
- Used 5-fold cross-validation to find best-performing configuration

####  Task 2: Cross-Validation & Regularization
- Applied L1 (Lasso) and L2 (Ridge) regularization
- Evaluated models using cross-validation scores

####  Task 3: Model Architecture Adjustment
- Experimented with alternative models: Random Forest Classifier
- Compared results with Logistic Regression baseline

### Milestone 3: Model Evaluation & Deployment Readiness

####  Task 1: Deployment Pipeline Setup *(Skipped optional steps)*
- Model was saved and loaded successfully (no versioning or monitoring setup as optional additions were avoided)

####  Task 2: Stress Testing & Validation
- Created an edge-case scenario (e.g., semiurban applicant with no credit history) and observed model prediction
- Validated model robustness

####  Task 3: Performance Evaluation
- Evaluated final model using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

---

##  Results Summary

| Model              | CV Accuracy | Test Accuracy |
|-------------------|-------------|----------------|
| Logistic Regression (Tuned) | 81.45%      | —              |
| Random Forest     | —           | 78.86%         |

- Both L1 and L2 regularized models achieved similar CV scores.
- Classification report showed high precision and recall for class `1` (approved).

---

##  Tools & Libraries Used
- Python
- Jupyter Notebook
- pandas, numpy
- scikit-learn (sklearn)
- matplotlib (if added)
- seaborn (if added)

---

##  How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

## Author
Sonu Tamang
 Newark, New Jersey
 MS in Business Analytics
 sonulama778@gmail.com
 🔗 [GitHub](https://github.com/Sonulama778)
🔗 [LinkedIn](https://linkedin.com/in/sonu-tamang)

