📊 Bike Rental Demand Analysis

📌 Project Overview



This project analyzes bike rental demand using Exploratory Data Analysis (EDA) and advanced data mining techniques. The goal is to identify key factors influencing rentals and build predictive models using Python.



📂 Dataset



Source: day.csv (Bike Sharing Dataset)



Target variable: cnt (total daily bike rentals)



Features include weather, seasonal, and time-based variables



🧭 Phase 1: Exploratory Data Analysis (EDA)



Cleaned and prepared the dataset (handled missing values, formatting, renaming columns)



Explored distributions, seasonality, and trends using visualizations



Identified strong relationships between temperature, seasonality, and rental demand



Removed leakage variables (casual, registered) before modeling



⚙️ Phase 2: Data Mining Methods

🔹 Random Forest Regression



Used to quantify feature importance and predict rental demand



Achieved strong performance (R² ≈ 0.85)



Key drivers: temperature, season, humidity, and windspeed



🔹 Neural Network Regression (MLPRegressor)



Applied to capture non-linear relationships



Standardized features before training



Lower performance than Random Forest (R² ≈ 0.56), but useful for model comparison



📈 Model Comparison



Random Forest provided the most accurate and interpretable results



Neural Network validated non-linear patterns but underperformed for this dataset



✅ Conclusion



EDA revealed clear weather and seasonal patterns in bike rentals. Random Forest Regression effectively translated these insights into accurate predictions, while Neural Networks offered a secondary analytical perspective.



🛠️ Tools \& Technologies



Python (Pandas, NumPy, Scikit-learn, Matplotlib)



Jupyter Notebook / Google Colab

