# Titanic Survival Prediction - ML Model Comparison

## 📊 Project Overview
Built and compared 3 machine learning models to predict Titanic passenger survival rates.

## 🎯 Results Summary

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 75.68% |
| Decision Tree | **75.68%** ✓ Best |
| Random Forest | 70.27% |

**Best Model: Decision Tree with 75.68% accuracy**

## 📈 Dataset Details
- **Total Records:** 183 (after cleaning)
- **Features:** Passenger Class, Age, Sex, Siblings/Spouses, Parents/Children, Fare, Embarked Port
- **Target:** Survived (0 = No, 1 = Yes)

## 🛠️ Data Processing Pipeline

### 1. Data Cleaning
- Removed rows with missing values
- Handled categorical variables
- Prepared data for ML models

### 2. Feature Engineering
- Converted categorical variables (Sex, Embarked) to dummy variables
- Created binary features for model training

### 3. Data Splitting
- 80% training data, 20% test data
- Random state = 42 (reproducibility)

## 🤖 Models Trained

### Model 1: Logistic Regression
- **Accuracy:** 75.68%
- Linear classification model
- Fast training and prediction

### Model 2: Decision Tree ⭐ (BEST)
- **Accuracy:** 75.68%
- Tree-based decision rules
- Highly interpretable results
- **Winner on this dataset**

### Model 3: Random Forest
- **Accuracy:** 70.27%
- Ensemble of 100 decision trees
- More complex, but underperformed
- Key learning: Complexity ≠ Better results

## 💡 Key Learnings
1. Data cleaning is critical for model performance
2. Complex models don't always outperform simpler ones
3. Testing multiple algorithms helps find the best fit
4. Visualization helps communicate results clearly

## 🔧 Technologies Used
- **Python 3**
- **Pandas** - Data processing
- **Scikit-learn** - Machine Learning
- **Matplotlib** - Visualization

## 📖 How to Use
1. Open the notebook file
2. Run it in Kaggle or Jupyter
3. See the results and visualizations

## 🎓 Skills Demonstrated
✓ Data Cleaning & Preprocessing
✓ Feature Engineering
✓ Model Training
✓ Model Evaluation
✓ Model Comparison
✓ Data Visualization

---
**Created:** April 2026 | ML Learning Project
