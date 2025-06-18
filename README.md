# PRODIGY-ML_TASK01
🏠 House Price Prediction using Linear Regression
This project implements a Linear Regression model to predict the prices of houses based on features like square footage, number of bedrooms, and number of bathrooms, using the Kaggle dataset: House Prices - Advanced Regression Techniques.

📌 Problem Statement
Predict the sale prices of houses using:

Square footage

Number of bedrooms

Number of bathrooms

📁 Dataset
The dataset used is train.csv from Kaggle, which includes:

Numeric features like GrLivArea (Above ground living area square feet)

Categorical features like Neighborhood

Target variable: SalePrice

📊 Exploratory Data Analysis
Checked for null values and handled them appropriately

Visualized correlations between features and sale price

Dropped unnecessary or highly null columns like Alley, GarageYrBlt, etc.

🛠️ Features Used
For model training, the following simplified features were used:

GrLivArea (square footage)

BedroomAbvGr (bedrooms)

FullBath (bathrooms)

🧠 Model
We used Scikit-Learn’s LinearRegression model to:

Train on selected features

Evaluate using Mean Squared Error and R² Score

🚀 Getting Started
1. Clone the Repository

git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
2. Install Requirements

pip install -r requirements.txt
3. Run the Notebook

jupyter notebook Final\ Projects\ Kaggle.ipynb
📈 Results
The model predicts house prices based on input features. Future improvements can include:

Using more features

Feature engineering

Trying ensemble models like XGBoost or Random Forests

📂 File Structure

.
├── Final Projects Kaggle.ipynb   # Jupyter notebook with all steps
├── train.csv                     # Training data from Kaggle
├── README.md                     # Project documentation
├── requirements.txt              # Python dependencies


✅ Requirements
numpy
pandas
matplotlib
seaborn
scikit-learn
