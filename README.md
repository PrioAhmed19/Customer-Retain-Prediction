# Customer Churn Prediction



---

## ⚙️ Key Features
- End-to-end data preprocessing and churn prediction workflow  
- Automated feature engineering and scaling  
- Rich exploratory data visualizations  
- Multiple ML model comparisons with metrics  
- Transformer-based deep learning integration  
- Hyperparameter tuning using **Optuna**  
- Model interpretability through feature importance plots  

---

## 🧩 Methodology

### 1. **Data Preprocessing**
- Imported dataset and removed duplicates, missing values, and irrelevant columns  
- Encoded categorical variables with `LabelEncoder`  
- Standardized numerical features using `StandardScaler`

### 2. **Exploratory Data Analysis (EDA)**
- Visualized churn distribution and behavior trends  
- Relationship analysis between:
  - Age vs Churn  
  - Satisfaction Score vs Churn  
  - Spending Patterns  
  - Support Contact Frequency  

### 3. **Feature Engineering**
- Constructed new interaction-based and ratio features:
  - `Average_Transaction_Amount`
  - `Years_as_Customer`
  - `Num_of_Support_Contacts`

### 4. **Model Training**
Trained and compared:
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM  
- CatBoost  
- Transformer-based Neural Network (Keras)

### 5. **Hyperparameter Optimization**
Used **Optuna** for automatic search and pruning



---

## ⚡ How to Use
1. Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
2. Upload the notebook file.
3. Run all cells sequentially.
4. All dependencies and datasets are handled inside the notebook—no additional configuration needed.



