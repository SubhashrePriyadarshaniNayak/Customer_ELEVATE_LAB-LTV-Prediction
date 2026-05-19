# Customer Lifetime Value (LTV) Prediction Model

## 📌 Project Overview
This project aims to predict the Customer Lifetime Value (LTV) based on historical purchase behavior. It helps businesses identify high-value customers and improve targeted marketing strategies.

## 🎯 Objective
- Predict customer lifetime value using machine learning  
- Perform customer segmentation based on predicted LTV  
- Assist in business decision-making and marketing optimization  

## 📊 Dataset
Dataset Name: Online Retail Dataset  

Features:
- Customer ID  
- Invoice Number  
- Quantity  
- Unit Price  
- Invoice Date
  Dataset is not included due to size constraints.
It can be downloaded from the original source.  

## ⚙️ Data Preprocessing
- Removed missing Customer IDs  
- Removed cancelled transactions  
- Created new feature:  
  TotalAmount = Quantity × UnitPrice  

## 🧠 Feature Engineering
- Recency: Days since last purchase  
- Frequency: Number of purchases  
- AOV (Average Order Value): Total Spend / Frequency  

## 📈 LTV Calculation
LTV = Frequency × AOV  

Note: This is a simplified approach due to lack of future transaction data.

## 🤖 Model Used
- XGBoost Regressor  
Reason:
- Handles non-linear relationships  
- Provides high accuracy  

## 📉 Model Evaluation
- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  

## 📊 Results & Visualizations
- LTV Distribution  
- Feature Importance  
- Actual vs Predicted Values  

## 👥 Customer Segmentation
- High Value Customers  
- Medium Value Customers  
- Low Value Customers  

## 📁 Project Structure
- LTV_Project.ipynb  
- Final_LTV_Predictions.csv  
- ltv_prediction_model.pkl  
- ltv_scaler.pkl  
- online_retail_II.csv  
- Project_Report.pdf  
- README.md  

## 🚀 How to Run
1. Install required libraries:
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn  

2. Run the notebook:
   LTV_Project.ipynb  

## 🔮 Future Scope
- Use real future data for better LTV prediction  
- Deploy as a web application  
- Apply advanced machine learning models  

## 📌 Conclusion
This project demonstrates how machine learning can be used to predict customer value and support data-driven marketing strategies.

## 👤 Author
Subhashree Priyadarshani Nayak
