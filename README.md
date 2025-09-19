# 💻 Laptop Price Prediction using Machine Learning

This project predicts **laptop prices** based on their specifications (such as processor, RAM, storage, GPU, operating system, etc.) using machine learning models.

##  Project Overview
- Cleaned and preprocessed laptop dataset
- Performed **feature engineering** (encoding categorical variables, scaling numerical features)
- Built and compared different **machine learning regression models**
- Evaluated models using **MAE, RMSE, and R² score**
- Visualized feature importance and model performance

##  Tech Stack
- **Python**
- **Pandas, NumPy** – Data handling
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – ML models and evaluation
- **Pickle/Joblib** – Model saving

## Machine Learning Models Used
- Linear Regression
- Ridge & Lasso Regression
- Random Forest Regressor
- Gradient Boosting / XGBoost (if included)

##  Evaluation Metrics
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**
## Results

## The best-performing model achieved:
- MAE: ~ (1774600.3135)
- RMSE: ~ (2858066.1129)
- R² Score: ~ (0.75)
- 
<img width="800" height="800" alt="scatter_actual_vs_pred" src="https://github.com/user-attachments/assets/89e00ae8-2bd7-43bd-b1f8-2522b16bd683" />

## Future Work
- Deploy model with Streamlit/Flask for interactive predictions
- Improve accuracy using advanced models (XGBoost, LightGBM, CatBoost)
- Expand dataset with latest laptops 


##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Laptop-Price-Prediction-using-ML.git
   cd Laptop-Price-Prediction-using-ML
