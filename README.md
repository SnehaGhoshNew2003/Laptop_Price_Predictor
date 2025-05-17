# Laptop Price Predictor

This project builds a **machine learning model** to predict laptop prices using multiple regression techniques.

## Features
- **Data Preprocessing:** Uses `ColumnTransformer` and `OneHotEncoder` for feature transformation.
- **Model Training:** Implements multiple regression models:
  - **Linear Regression**
  - **Decision Tree Regressor**
  - **Random Forest Regressor**
  - **K-Nearest Neighbors (KNN)**
  - **Support Vector Regression (SVR)**
- **Ensemble Learning:** Uses `VotingRegressor` to combine multiple models.
- **Pipeline Creation:** Implements a streamlined ML pipeline.
- **Visualization:** Uses `matplotlib` for data analysis.

## Technologies Used
- **pandas** (Data manipulation)
- **numpy** (Numerical operations)
- **scikit-learn** (ML model training & evaluation)
- **matplotlib** (Data visualization)

## Installation
Install the required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Laptop_Price_Predictor.git
cd Laptop_Price_Predictor
```
2. Run the Jupyter Notebook:
```bash
jupyter notebook laptop_price_predictor.ipynb
```
3. Follow the notebook instructions to preprocess data, train models, and make predictions.

## Example Output
- **Input:** Laptop specifications (RAM, processor, GPU, brand, etc.)
- **Output:** Predicted laptop price

## Contributing
Feel free to submit issues or pull requests to improve this project.
