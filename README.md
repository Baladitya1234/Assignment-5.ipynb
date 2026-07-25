# Employee Attrition Prediction using Decision Tree and Random Forest

## Objective

The objective of this project is to predict employee attrition using Machine Learning classification algorithms. Decision Tree and Random Forest models are developed, trained, and evaluated to determine which model provides better prediction accuracy and performance.

---

## Dataset

**IBM HR Analytics Employee Attrition & Performance Dataset**

Kaggle Link:
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Methodology

1. Imported the required Python libraries.
2. Loaded the IBM HR Analytics dataset.
3. Displayed the first five records.
4. Explored dataset information and summary statistics.
5. Identified numerical and categorical features.
6. Checked for missing values.
7. Removed unnecessary columns.
8. Encoded categorical variables using LabelEncoder.
9. Split the dataset into training (80%) and testing (20%) sets.
10. Trained a Decision Tree Classifier.
11. Trained a Random Forest Classifier with 100 estimators.
12. Predicted employee attrition using both models.
13. Evaluated the models using:
    - Accuracy
    - Precision
    - Recall
    - F1-Score
14. Generated confusion matrices.
15. Visualized feature importance for the Random Forest model.
16. Compared the performance of both models.

---

## Results

Both Decision Tree and Random Forest models were successfully trained and evaluated. Performance was measured using Accuracy, Precision, Recall, and F1-Score. Confusion matrices were generated for both models, and feature importance was analyzed using the Random Forest classifier.

---

## Model Comparison

| Model | Advantages | Limitations |
|-------|------------|-------------|
| Decision Tree | Easy to understand and interpret | Can overfit the training data |
| Random Forest | Higher accuracy and better generalization | Requires more computation and is less interpretable |

---

## Conclusion
In this assignment, Decision Tree and Random Forest classifiers were developed to predict employee attrition. After evaluating both models using Accuracy, Precision, Recall, and F1-score, the Random Forest model performed better than the Decision Tree model. This is because Random Forest combines the predictions of many decision trees, reducing overfitting and improving generalization. Decision Trees are simple and easy to interpret, but they often overfit the training data, leading to lower performance on unseen data. On the other hand, Random Forest provides higher accuracy and more reliable predictions, although it requires more computational resources and is harder to interpret. Feature importance analysis showed the most influential factors affecting employee attrition. Overall, Random Forest is the preferred model for this classification problem because of its better predictive performance and robustness.
**Course:** B.Tech – Computer Science and Engineering

**Assignment:** Employee Attrition Prediction using Decision Tree and Random Forest
