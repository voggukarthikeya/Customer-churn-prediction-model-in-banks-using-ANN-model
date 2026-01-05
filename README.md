# 🧠 Credit Card Bank Churner Prediction using ANN

This repository contains a Jupyter Notebook that builds and evaluates an **Artificial Neural Network (ANN)** to predict whether a customer will churn from a bank's credit card service.

## 📁 File Structure

- `credit card bank churner.ipynb` — Main notebook containing data preprocessing, ANN model building, training, and evaluation.

## 📊 Project Overview

**Objective:**  
To develop a predictive model using an Artificial Neural Network to identify customers likely to churn from a credit card service, based on their demographics and account activity.

**Dataset Features Include:**
- Demographic data (e.g., age, gender, marital status)
- Credit card usage statistics (e.g., transaction value, credit limit)
- Account information (e.g., tenure, balance)
- Target variable: `Attrition_Flag` (Existing vs. Attrited Customers)

## ⚙️ Technologies Used

- Python 🐍  
- Pandas, NumPy — Data manipulation  
- Matplotlib, Seaborn — Data visualization  
- TensorFlow / Keras — ANN model building and training  
- Scikit-learn — Preprocessing and evaluation  
- Jupyter Notebook — Development interface  

## 🧪 Key Steps

1. **Data Exploration & Preprocessing**
   - Summary statistics
   - Encoding categorical variables
   - Feature scaling
2. **Model Building: ANN**
   - Input layer with relevant features
   - Hidden layers with activation functions (e.g., ReLU)
   - Output layer with sigmoid activation for binary classification
3. **Model Training & Validation**
   - Binary cross-entropy loss
   - Optimizer (e.g., Adam)
   - Accuracy metric
4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix and ROC Curve

## 📈 Model Performance

The final ANN model achieved:
- **Accuracy**: _[Insert Accuracy]_
- **F1 Score**: _[Insert F1 Score]_

Evaluation metrics are visualized and explained in the notebook.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/prateek-g-bit/credit-card-churn-ann.git
   cd credit-card-churn-ann
2. Install dependencies:
   pip install -r requirements.txt
3. Launch the notebook:
   jupyter notebook
4. Open credit card bank churner.ipynb to run the code step by step.

##  🔮 Future Enhancements
     Hyperparameter tuning with KerasTuner or GridSearch

     Deployment as an interactive web app using Streamlit or Flask

     Model interpretability with SHAP or LIME
