Task 16: Hyperparameter Tuning using GridSearchCV
Objective

The objective of this task is to optimize a machine learning model using GridSearchCV for hyperparameter tuning. The task demonstrates how to improve model performance through systematic parameter search and cross-validation.

Dataset

Dataset Used: Breast Cancer Wisconsin Dataset

Source: sklearn.datasets.load_breast_cancer()

Total Samples: 569

Features: 30 numerical features

Target Classes:

0 → Malignant

1 → Benign

Tools and Libraries Used

Python

NumPy

Pandas

Scikit-learn

Joblib

Model Used

Support Vector Machine (SVM)

Concepts Implemented

Train-test split

Feature scaling using StandardScaler

Hyperparameter tuning

Cross-validation

Model comparison

Saving optimized model

Steps Performed

Loaded and explored the Breast Cancer dataset.

Split the dataset into training and testing sets.

Applied feature scaling using StandardScaler.

Trained a default SVM model.

Defined a hyperparameter grid including:

C (Regularization parameter)

gamma (Kernel coefficient)

kernel (rbf, linear)

Applied GridSearchCV with 5-fold cross-validation.

Extracted best parameters.

Compared tuned model performance with default model.

Saved the best model using Joblib.

Hyperparameters Tuned
Parameter	Description
C	Controls regularization strength
gamma	Kernel coefficient for non-linear decision boundary
kernel	Type of decision boundary function
Model Performance Comparison
Model	Accuracy
Default SVM	Baseline accuracy
Tuned SVM	Improved accuracy after tuning

Observation:

Hyperparameter tuning improved model performance.

Cross-validation ensured reliable parameter selection.

Tuned model generalized better on unseen data.

Deliverables

Jupyter Notebook (.ipynb)

Best Parameters Output

Performance Comparison Table

Saved Tuned Model (best_svm_tuned_task16.pkl)

Final Outcome

The intern successfully implemented hyperparameter tuning using GridSearchCV, optimized SVM performance using cross-validation, and demonstrated understanding of model improvement techniques used in industry ML workflows.

Key Learnings

Difference between model parameters and hyperparameters

Importance of cross-validation

Preventing overfitting during tuning

Model optimization techniques

GridSearch vs RandomizedSearch

How to Run

Clone the repository

Open the notebook in Jupyter Notebook or VS Code

Run all cells sequentially

✅ Task 16 Completed Successfully
