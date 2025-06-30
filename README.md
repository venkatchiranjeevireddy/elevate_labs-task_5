# elevate_labs-task_5
# 🩺 Heart Disease Prediction using Decision Tree & Random Forest

This project trains and evaluates Decision Tree and Random Forest classifiers on heart disease data using patient features like age, sex, blood pressure, cholesterol, and more.

## 📁 Dataset

The dataset includes these columns:

- `age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`, `target`
- `target` is the label: 0 = No Heart Disease, 1 = Heart Disease

## ✅ Tasks Performed

1. **Train a Decision Tree Classifier** and **visualize** the tree
2. **Analyze overfitting** and control tree depth
3. **Train a Random Forest** and compare performance
4. **Interpret Feature Importances**
5. **Evaluate using Cross-Validation**
6. **Build a Gradio App** for live predictions

## 📊 Algorithms Used

### 1. Decision Tree Classifier

- Mimics human decision logic using "if-else" rules
- Uses Gini Impurity or Entropy to split nodes
- Prone to overfitting without max_depth or pruning

### 2. Random Forest Classifier

- Ensemble of multiple decision trees trained on bootstrapped samples
- Each tree uses random subsets of features
- Reduces overfitting and improves generalization

## 📐 Evaluation Metrics

- Accuracy
- Cross-validation score (5-fold)
- Confusion Matrix
- Feature Importance

## 🖥️ Gradio App

An interactive web interface is built using [Gradio](https://gradio.app). Users can:

- Choose model (Decision Tree or Random Forest)
- Enter patient info
- Get prediction: **"Disease"** or **"No Disease"**

## 🚀 How to Run

1. Install required packages:
```bash
pip install -r requirements.txt
