# Predicting the Success of Bank Telemarketing

## 📌 Overview
This project aims to predict the success of a bank's telemarketing campaigns using machine learning models. By leveraging exploratory data analysis (EDA), data preprocessing, and various classification techniques, we achieved a maximum F1 score of **93%**.

## 📊 Dataset
The dataset consists of **39,211** records with the following key features:
- **Client Information:** Age, job, marital status, education, balance, default history, housing loan, personal loan.
- **Campaign Details:** Contact method, last contact date, duration, number of contacts, previous campaigns.
- **Response Variable:** Whether the client subscribed to the service (target variable).

## 🛠️ Data Preprocessing
Key preprocessing steps performed:
- **Handling missing values**: Imputed missing values for categorical and numerical features.
- **Date conversion**: Transformed `last contact date` into useful time-based features.
- **Categorical encoding**: One-hot encoded categorical variables.
- **Feature scaling**: Normalized numerical features for better model performance.
- **Binning**: Converted continuous features into discrete intervals.
- **Handling class imbalance**: Applied techniques like SMOTE and class weighting.

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to understand:
- Distribution of numerical and categorical variables.
- Correlation between features.
- Trends in campaign success.
- Impact of different features on customer response.

## 🤖 Models Used
Trained multiple models and compared their performance:
- **Logistic Regression**
- **Stochastic Gradient Descent (SGD) Classifier**
- **K-Nearest Neighbors (KNN)**
- **Extreme Gradient Boosting (XGBoost)**
- **Principal Component Analysis (PCA) for dimensionality reduction**

## 📈 Results
- The best model achieved an **F1 score of 93%**.
- XGBoost performed the best among the classifiers.
- Feature engineering and data balancing significantly improved model accuracy.

## ⚙️ Installation and Usage
###  Prerequisites
Ensure you have Python installed along with the required dependencies:
```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn
```

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bank-telemarketing-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bank-telemarketing-prediction
   ```
3. Run the preprocessing and training script:
   ```bash
   python train.py
   ```
4. 📊 Evaluate the results using the evaluation notebook.

## 📉 Visualizations
- Heatmaps for feature correlations.
- Distribution plots of numerical features.
- Success rates for different customer segments.

## 🏆 Conclusion
This project successfully predicted telemarketing campaign success using ML models, achieving a **93% F1 score**. Future work includes:
- Hyperparameter tuning for further performance improvement.
- Deploying the model as an API for real-time prediction.


