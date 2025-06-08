# 🏡 House Price Prediction using XGBoost

This machine learning project predicts house prices in California using various features such as median income, number of rooms, and location characteristics. The model is built using the XGBoost Regressor.

## 📊 Dataset

The project uses the **California Housing dataset** from Scikit-learn, which includes the following features:

- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block group
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Block group population
- `AveOccup`: Average number of household members
- `Latitude`: Block group latitude
- `Longitude`: Block group longitude

The target variable is **`price`** (Median house value for households within a block group).

## 🧠 Model Used

- **XGBoost Regressor** – a high-performance gradient boosting framework
- Performance metrics:
  - R² Score (for both training and test sets)
  - Mean Absolute Error

## 📈 Visualizations

- Correlation heatmap of features
- Scatter plot comparing actual vs. predicted house prices

## 🛠️ Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Seaborn, Matplotlib
- Google Colab / Jupyter Notebook

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/House_Price_Prediction.git
   cd House_Price_Prediction
