# Predicting the Success of Bank Telemarketing

## 📌 Overview
This project aims to predict the success of a bank's telemarketing campaigns using machine learning models. By leveraging exploratory data analysis (EDA), data preprocessing, and various classification techniques, we achieved a maximum F1 score of **93%**.

## 📊 Dataset
The dataset consists of **39,211** records with the following key features:
- **Client Information:** Age, job, marital status, education, balance, default history, housing loan, personal loan.
- **Campaign Details:** Contact method, last contact date, duration, number of contacts, previous campaigns.
- **Response Variable:** Whether the client subscribed to the service (target variable).

<div align="center">
   <img src="https://github.com/user-attachments/assets/d848509e-0728-490b-b2d5-96b6cbcdef46">
   <p>Fig: Dataset sample</p>
</div>

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

## 📉 Visualizations
- Heatmaps for feature correlations.
- Distribution plots of numerical features.
- Success rates for different customer segments.
  
<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/d7d40775-e815-4979-9203-7384677f713e" width="300">
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/b6133302-29e4-4a3c-a58d-a91ba8c9aea2" width="300">
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/6729d210-3383-40be-a592-f90227feea8c" width="300">
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/37eca970-b2ed-49c0-984b-048609e14a24" width="300">
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/8e00429d-540d-4eb5-b06f-ac4f95a7af3f" width="300">
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/65416d7d-fca4-4a2e-9301-5e64b8bcf5e4" width="300">
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/1f00c017-0c6f-42d3-b07b-952363dfcab0" width="300">
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/aae362ac-677e-4fdb-8afc-6ffb5c9db175" width="300">
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/c1ee9eed-4246-4f2b-b6f5-dac332f27461" width="300">
    </td>
  </tr>
</table>



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
   git clone https://github.com/yourusername/bank-telemarketing-success.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bank-telemarketing-success
   ```

3. Check out the notebook.

## 🏆 Conclusion
This project successfully predicted telemarketing campaign success using ML models, achieving a **93% F1 score**. 


