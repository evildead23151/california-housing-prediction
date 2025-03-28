California Housing Price Prediction

Project Overview

This project implements a Real Estate Price Prediction Model using California housing data, based on Chapter 2 of "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow (2nd Edition)" by Aurélien Géron.

The project explores data preprocessing, feature engineering, model training, and evaluation to predict median house values.

Dataset

The dataset used in this project is the California Housing Prices dataset, which contains information about various housing features such as:

Median income of residents

House age

Total rooms & bedrooms

Population

Households

Latitude & Longitude

Median house value (target variable)

Installation & Setup

Clone the repository:

git clone https://github.com/evildead23151/README.md

Navigate to the project directory:

cd your-repo

Install the required dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook RealEstatePricePredictionModel.ipynb

Key Steps in the Notebook

Data Loading: Fetch the dataset using fetch_california_housing() or load from CSV.

Exploratory Data Analysis (EDA): Histograms, correlations, and geospatial visualizations.

Data Preprocessing: Handling missing values, feature scaling, and transformations.

Data Splitting: Train-test split with StratifiedShuffleSplit.

Feature Engineering: Creating meaningful attributes (e.g., rooms_per_household).

Model Training: Regression models including:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Model Evaluation: Using RMSE and cross-validation.

Results

The Random Forest Regressor performed the best with the lowest RMSE.

Feature engineering improved model performance significantly.

Future Enhancements

Hyperparameter tuning using GridSearchCV.

Try advanced models like XGBoost or Neural Networks.

Deploy as a web app using Flask or FastAPI.

Author

Gitesh Malik

License

This project is licensed under the MIT License.
