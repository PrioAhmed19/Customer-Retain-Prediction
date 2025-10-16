This Jupyter notebook provides a production-ready, end-to-end pipeline for customer churn prediction with advanced machine learning techniques and comprehensive analysis. It is designed for easy execution: simply upload to Google Colab and run all cells—no additional setup required.

🚀 Key Features & Improvements
1. Advanced Optimization with Optuna

Hyperparameter Tuning: 30 trials per model for thorough exploration.

Cross-Validation: Stratified 5-fold CV for robust evaluation.

Models Optimized: Random Forest, XGBoost, LightGBM, and ANN.

Insights: Parameter importance analysis for each model.

2. Handling Class Imbalance

No SMOTE Used: Avoids oversampling pitfalls and information leakage.

Class Weights: Provides more realistic and generalizable results.

3. Ensemble Model

Weighted Voting: Combines predictions from all optimized models based on CV performance.

Performance Boost: Leverages strengths of individual models for higher accuracy.

4. Enhanced Cross-Validation

Stratified 5-fold CV applied across all models.

Cross-validation scores visualized for better interpretability.

5. Comprehensive Analysis

Data Understanding:

Exploratory Data Analysis (EDA) with 10+ visualizations.

Correlation and trend analysis for feature insights.

Feature Engineering:

10+ engineered features including RFM and engagement scores.

Domain-specific features for improved churn prediction.

Model Training & Evaluation:

Training of 4 base models + 1 ensemble.

Detailed performance evaluation with multiple metrics:

Accuracy, F1-score, Precision, Recall, ROC-AUC

Confusion matrices, ROC curves, and classification reports

Feature importance analysis and visualizations.

⚡ How to Use

Open Google Colab: https://colab.research.google.com

Upload the notebook file.

Run all cells sequentially.

All dependencies and datasets are handled inside the notebook. No additional configuration needed.

🛠 Technology & Libraries

Python 3.x

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn, XGBoost, LightGBM

TensorFlow/Keras (for ANN)

Optuna (for hyperparameter optimization)
