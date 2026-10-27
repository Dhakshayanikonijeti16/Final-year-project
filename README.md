# Final Year Project
# BigMart Sales Prediction using Machine Learning

## About the Project

This project is a Machine Learning project that predicts **Item Outlet Sales** for BigMart products.

The main goal of this project is to understand how different product and outlet-related factors affect sales and to build a machine learning model that can predict sales.

This is a **Supervised Learning – Regression** problem because the target variable, `Item_Outlet_Sales`, is a numerical value.

## Dataset

The project uses the BigMart sales dataset.

The dataset contains information such as:

- Item weight
- Item fat content
- Item visibility
- Item type
- Item MRP
- Outlet identifier
- Outlet establishment year
- Outlet size
- Outlet location type
- Outlet type
- Item outlet sales

The dataset contains **8,523 records and 12 columns**.

## Project Steps

The project follows these main steps:

1. **Define the problem and goal**
2. **Collect and understand the data**
3. **Data preprocessing**
4. **Feature engineering and Exploratory Data Analysis (EDA)**
5. **Feature selection**
6. **Train-test split**
7. **Build and evaluate the Machine Learning model**
8. **Conclusion**

## Data Preprocessing

The dataset was checked for missing values and data types.

Missing values were handled using:
- Mean for `Item_Weight`
- Mode for `Outlet_Size`

Categorical variables were converted into numerical variables using one-hot encoding.

## Machine Learning Model

The project uses **XGBoost Regressor** for predicting `Item_Outlet_Sales`.

Feature importance was also analyzed to identify the variables that have a stronger influence on sales. Some of the important features include outlet type, outlet size, outlet age, and item MRP.

## Results

The final XGBoost model achieved:

- **R² Score:** 0.7428
- **MSE:** 0.2704
- **RMSE:** 0.5200

These results show that the model can explain a substantial portion of the variation in BigMart outlet sales.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab
- GitHub

## Files in this Repository

- `final_year.ipynb` – Complete machine learning project notebook
- `train.csv` – Dataset used for training and analysis
- `README.md` – Project description

## How to Run

1. Download or clone this repository.
2. Open `final_year.ipynb` in Google Colab or Jupyter Notebook.
3. Make sure `train.csv` is available in the same working directory.
4. Run the notebook cells step by step.

## Conclusion

This project demonstrates how Machine Learning can be used to predict BigMart sales based on product and outlet characteristics. The project includes data preprocessing, exploratory analysis, feature engineering, feature selection, model training, and evaluation using XGBoost.
