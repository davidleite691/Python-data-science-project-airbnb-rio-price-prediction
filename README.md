# 🏠 Airbnb Rio – Intelligent Property Price Prediction

A Data Science project developed to predict the ideal daily rental price for properties listed on Airbnb in Rio de Janeiro.

The goal is to provide an accessible tool for both property owners and guests, helping estimate fair prices based on property characteristics and market conditions.

## 🚀 Demo

The application was deployed using Streamlit, allowing users to enter property information and receive a real-time price prediction.

🔗 To access the application:
pip install -r requirements.txt
run: streamlit run c:\path\Deploy_projeto_airbnb.py.


---

# 📌 Business Problem

Airbnb hosts need to define the daily rental price of their properties while considering several factors, such as:

- Location
- Number of bedrooms
- Guest capacity
- Available amenities
- Hosting policies
- Time of the year

Setting an inappropriate price may result in low occupancy rates or lost revenue opportunities.

This project aims to solve this problem by using Machine Learning to automatically estimate the ideal rental price for a property.

---

# 🎯 Objectives

## For Property Owners

Enable hosts to determine how much they should charge for their property based on its characteristics.

## For Guests

Help travelers identify attractive listings by comparing the advertised price with the price estimated by the model.

---

# 📊 Dataset

The data used in this project was obtained from Kaggle:

📂 Dataset:  
https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro

Reference notebook:  
https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb

### Dataset Information

- Airbnb listings from Rio de Janeiro
- Period: April 2018 to May 2020
- Exception: June 2018 dataset is not available
- Prices are expressed in Brazilian Reais (R$)
- Includes property details, location information, accommodations, and rental prices

---

# 🔬 Methodology

The project follows the main stages of the Data Science lifecycle:

## 1. Business Understanding

Definition of the business objective and understanding of user needs.

## 2. Data Understanding

Analysis of the available variables and identification of potential factors influencing property prices.

## 3. Data Collection

Importing and consolidating the monthly datasets.

## 4. Data Cleaning and Preprocessing

- Removal of inconsistent values
- Handling missing values
- Variable standardization
- Data type conversion

## 5. Exploratory Data Analysis (EDA)

Investigation of the data to identify:

- Distributions
- Correlations
- Outliers
- Variable influence on price

## 6. Feature Engineering

Creation and transformation of features to improve model performance.

## 7. Modeling

Training and comparison of Machine Learning regression algorithms.

Examples:

- Linear Regression
- Random Forest Regressor
- Extra Trees Regressor
- XGBoost (if used)

## 8. Model Evaluation

Comparison of models using metrics such as:

- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

## 9. Deployment

Development of a Streamlit web application to make the model accessible to end users.

---

# 💡 Initial Hypotheses

During the exploratory analysis phase, several hypotheses were considered:

## Seasonality

Vacation periods and peak tourist seasons, especially December, tend to have higher daily rental prices.

## Location

Property location is expected to have a strong influence on price due to factors such as:

- Safety
- Proximity to beaches
- Tourist attractions
- Infrastructure

## Amenities

Features such as:

- Air conditioning
- Swimming pool
- Wi-Fi
- Parking

may significantly increase the property's rental value.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Streamlit
- Joblib

---

# 📈 Results

The developed model was able to identify relevant pricing patterns and provide consistent predictions based on property characteristics.

In addition, the web application allows users to generate predictions quickly and intuitively without requiring technical knowledge.

---

# ▶️ How to Run the Project

Run the notebook file `Solução Airbnb Rio.ipynb` to generate the `modelo.joblib` file (the trained Machine Learning model).

Since GitHub does not allow files larger than 100 MB, the trained model could not be uploaded to this repository.

After generating the model file, run the deployment script to start the Streamlit application.

---

# 👨‍💻 Author

Developed by **David Luís Leite de Oliveira**.

📧 davidluisleite22@gmail.com

🔗 www.linkedin.com/in/david-luís-leite

---

# 📄 License

This project was developed for educational purposes and as a learning exercise in Data Science and Machine Learning.
