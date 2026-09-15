                                📅✈️ Flight Fare Prediction Project 📅✈️

A regression-based machine learning project designed to predict flight ticket prices by benchmarking multiple algorithms and deploying the winning model as a live prediction app.

📌 Project Overview

This project analyzes flight booking data using Python and Scikit-Learn to predict ticket prices based on airline, route, timing, and duration factors.

The project contains **10,682 flight booking records** covering airline, source, destination, date, time, and duration information.

The analysis focuses on feature engineering, benchmarking multiple regression algorithms, and deploying the best-performing model as a working app — not stopping at a notebook result.

🎯 Project Objectives

- Engineer predictive features from raw date, time, and duration data
- Encode categorical variables (Airline, Source, Destination) for modeling
- Benchmark multiple regression algorithms on the same train/test split
- Select the best-performing model based on unseen test-set accuracy
- Validate against overfitting via train/test performance comparison
- Deploy the final model as a live, usable prediction app

🛠️ Technologies Used

🐍 Python
- Data manipulation and modeling

📊 Pandas & NumPy
- Data cleaning, feature extraction, and transformation

🤖 Scikit-Learn, CatBoost, LightGBM, XGBoost
- Regression modeling and benchmarking

🌐 Flask
- Model deployment as a live web app

📓 Jupyter Notebook
- Exploratory analysis and model development

📁 Dataset

- 📊 10,682 flight booking records
- ✈️ Fields: Airline, Source, Destination, Date of Journey, Departure/Arrival Time, Duration, Total Stops, Price

🔑 Key Data Fields

- Airline
- Source / Destination
- Date, Time, Duration
- Number of Stops
- Price (target variable)

⚙️ Feature Engineering

- Extracted 12 predictive features from raw date, time, and duration components
- Encoded categorical variables (Airline, Source, Destination) for regression modeling

🤖 Model Benchmarking

Trained and benchmarked 6 regression algorithms on a 70/30 train-test split:

- AdaBoost
- Extra Trees
- Random Forest
- CatBoost
- LightGBM
- XGBoost

📈 Model Selection & Validation

- Compared R² across all 6 algorithms on unseen test data
- Validated train/test performance to check for overfitting before finalizing
- Selected the final model based on test-set performance, not training-set accuracy alone

🚀 Deployment

The winning model was packaged into a Flask app (`app.py`) so fare predictions can be generated live, not just read from a notebook.

💡 Key Business Insights

- Flight prices vary significantly based on airline, journey duration, and stops
- Travel date and departure timing strongly influence ticket prices
- Certain airlines consistently show higher average fares
- Tree-based ensemble methods outperformed simpler regressors on this dataset

⭐ Project Highlights

📊 Records Analyzed: 10,682

🎛️ Engineered Features: 12

🤖 Algorithms Benchmarked: 6

🏆 Best Model: CatBoost

📈 Best R² (Test Data): 84.15%

📉 R² Range (Other 5 Models): 43.9%–84.0%

🚀 Deployed: Live prediction app via Flask

