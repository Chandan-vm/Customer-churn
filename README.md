# 📉 Customer Churn Prediction
A machine learning project to predict customer churn using classification algorithms. This project helps businesses understand which customers are likely to leave and why, enabling better retention strategies.

## 📁 Project Structure
- `data/` – Dataset(s) used for training and testing
- `notebooks/` – Jupyter notebooks with data analysis, preprocessing, and model building
- `models/` – Saved model files
- `scripts/` – Python scripts for modular execution
- `README.md` – Project documentation

## 🧠 Problem Statement
Customer churn is a critical problem for telecom companies. In this project, we aim to predict which customers are at risk of churning based on demographic and service-related attributes.

## 🔍 Exploratory Data Analysis
- Checked for missing values and outliers
- Visualized churn rate by contract type, payment method, and tenure
- Found correlations between features using heatmaps

## ⚙️ Preprocessing
- Label encoding and one-hot encoding
- Feature scaling using StandardScaler
- Train-test split: 80/20

## 🧪 Model Building
Trained and evaluated the following models:
- Logistic Regression
- Decision Tree
- Random Forest

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## 🏆 Results

| Model            | Accuracy | F1-Score | ROC-AUC |
|------------------|----------|----------|---------|
| Logistic Reg.    | 0.80     | 0.72     | 0.83    |
| Random Forest    | 0.85     | 0.78     | 0.88    |

## 📌 Key Insights
- Customers with month-to-month contracts are more likely to churn
- High monthly charges correlate with higher churn
- Long tenure customers are less likely to churn

## 🚀 Future Improvements
- Hyperparameter tuning using GridSearchCV
- Feature engineering (e.g., customer tenure buckets)
- Deploy model with Flask or Streamlit

## 📚 Tools & Tech
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🙋‍♂️ About Me
I'm **Chandan M**, an aspiring data scientist passionate about solving real-world problems using data.  
Connect with me on [LinkedIn](https://www.linkedin.com/in/chandan-m-432204223).

## 📬 Contact
Feel free to reach out:
- 📧 Email: chandanshetty2000@gmail.com

