# SCT_DS_3
# Task 03 – Predicting Customer Purchase Using Decision Tree Classifier

---

This project aims to build a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on their **demographic** and **behavioral** attributes. The dataset used is the **Bank Marketing Dataset** from the **UCI Machine Learning Repository**.

---

## Objectives

- Load and preprocess the bank marketing dataset  
- Encode categorical features using `LabelEncoder`  
- Train a **Decision Tree classifier** to predict customer purchase decisions  
- Evaluate the model using accuracy, confusion matrix, and classification report  
- Visualize the trained decision tree and feature importances  

---

## Workflow Summary

1. Download and extract the dataset (`bank-additional-full.csv`)  
2. Encode categorical columns using `LabelEncoder`  
3. Map the target variable `y` from `yes`/`no` to `1`/`0`  
4. Split the dataset into training and testing sets (70/30)  
5. Train a `DecisionTreeClassifier` with a max depth of 5  
6. Predict and evaluate using:
   - Accuracy  
   - Confusion Matrix  
   - Classification Report  
7. Visualize:
   - Decision Tree  
   - Feature Importances  

---

## Technologies Used

- `Python 3.x`  
- `pandas`, `numpy` – data handling and analysis  
- `sklearn` – machine learning and model evaluation  
- `matplotlib` – visualization  
- Google Colab – runtime environment  

---

## Evaluation

- ✅ Dataset successfully downloaded and loaded  
- ✅ Categorical features encoded with `LabelEncoder`  
- ✅ Decision tree model trained with depth constraint  
- ✅ Accuracy achieved: **~88%** (may vary depending on dataset split)  
- ✅ Feature importance reveals top predictive variables  
- ✅ Model visualization saved as `decision_tree.png`  
- ✅ Evaluation results stored in `model_results.txt`  

---

## Notes

- The dataset is imbalanced, so class-wise precision and recall are crucial  
- The model is interpretable and useful for understanding decision rules  
- `max_depth=5` was used to avoid overfitting and ensure readability  
- Further improvements can include cross-validation, pruning, or boosting
