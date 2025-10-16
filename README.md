# Customer Churn Prediction


## 🚀 Key Features & Improvements

### Advanced Optimization with Optuna
- Hyperparameter tuning: 30 trials per model for thorough exploration.
- Stratified 5-fold cross-validation for robust evaluation.
- Models optimized: Random Forest, XGBoost, LightGBM, and ANN.
- Parameter importance analysis included.

### Handling Class Imbalance
- **No SMOTE** used: avoids oversampling pitfalls and information leakage.
- Class weights provide more realistic and generalizable results.

### Ensemble Model
- Weighted voting based on CV performance.
- Combines strengths of all optimized models for better performance.

### Enhanced Cross-Validation
- Stratified 5-fold CV applied across all models.
- Cross-validation scores visualized for better interpretability.

### Comprehensive Analysis
**Data Understanding**
- EDA with 10+ visualizations.
- Correlation and trend analysis for feature insights.

**Feature Engineering**
- 10+ engineered features including RFM and engagement scores.
- Domain-specific features for improved churn prediction.

**Model Training & Evaluation**
- Training of 4 base models + 1 ensemble.
- Performance evaluation with multiple metrics:
  - Accuracy, F1-score, Precision, Recall, ROC-AUC
  - Confusion matrices, ROC curves, classification reports
- Feature importance analysis and visualizations.

---

## ⚡ How to Use
1. Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
2. Upload the notebook file.
3. Run all cells sequentially.
4. All dependencies and datasets are handled inside the notebook—no additional configuration needed.

---

## 🛠 Technology & Libraries
- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, LightGBM
- TensorFlow/Keras (for ANN)
- Optuna (for hyperparameter optimization)

