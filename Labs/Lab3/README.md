# Lab 2: Building and Evaluating Classification Models

### What the Lab is About
This lab emphasizes building and evaluating classification models in practice. Topics covered include:

- Implementing Logistic Regression, Decision Trees, and Random Forests
- Comparing model performance using accuracy, precision, recall, F1-score, ROC/AUC, and confusion matrices
- Understanding model strengths, limitations, and interpretability
- Applying proper evaluation techniques to select and refine models

By the end, we gain practical experience in training, evaluating, and interpreting classification models effectively.

### What I Did
I implemented Logistic Regression, Decision Trees, and Random Forests on a classification dataset. I trained each model, made predictions, and evaluated them using different metrics (accuracy, precision, recall, F1-score, confusion matrix, and ROC/AUC). I also compared the results and tried some simple improvements like tuning hyperparameters.

### What I Learned
- How different classifiers work and when to use each one (Logistic Regression is fast and interpretable, Decision Trees are easy to understand but can overfit, Random Forests usually give better performance)
- The importance of using multiple metrics—not just accuracy—because accuracy can be misleading on imbalanced datasets
- How to read a confusion matrix and what precision/recall trade-offs mean
- ROC curves and AUC are great for comparing models overall

### Challenges
At first my Random Forest was not performing much better than the others, then I realized I needed more trees and proper depth limits. Tuning those parameters improved the scores a lot. I also got confused between precision and recall at the beginning, but after working with the confusion matrix on real predictions it became clear.

The notebook `Lab2_KhalidaBestani_ITAI1371.ipynb` (or your exact filename) contains all my code, results, visualizations, and comments.
