# Movie Rating Prediction

🎯 Project Overview

This project aims to predict IMDb movie ratings based on various attributes using machine learning techniques. The dataset includes information such as genre, director, actors, duration, and votes.

📌 Objectives

Perform data preprocessing (handling missing values, encoding categorical variables, feature engineering).

Train a Random Forest Regressor to predict movie ratings.

Evaluate the model's performance using appropriate metrics.

Maintain a well-structured GitHub repository with clear documentation.

📂 Project Structure

movie-rating-prediction/
│── data/
│   ├── IMDb_Movies_India.csv  # Original dataset
│   ├── cleaned_data.csv       # Processed dataset
│── notebooks/
│   ├── data_preprocessing.ipynb  # Data cleaning & feature engineering
│   ├── model_training.ipynb      # Model training & evaluation
│── src/
│   ├── preprocessing.py  # Script for data cleaning
│   ├── train_model.py    # Script to train and evaluate the model
│── requirements.txt      # List of dependencies
│── README.md             # Project documentation
│── .gitignore            # Ignore unnecessary files

🚀 How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/yourusername/movie-rating-prediction.git
cd movie-rating-prediction

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run Data Preprocessing

python src/preprocessing.py

4️⃣ Train the Model

python src/train_model.py

📊 Dataset Information

IMDb_Movies_India.csv → Original dataset.

cleaned_data.csv → Processed dataset after handling missing values and feature engineering.

🔍 Feature Engineering

Director Success Rate – Average rating of past movies by the same director.

Genre Average Rating – Mean rating of all movies in the same genre.

🏆 Model Performance

Mean Absolute Error (MAE): 0.34

Mean Squared Error (MSE): 0.21

R² Score: 0.87

🛠 Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn

Model Used: Random Forest Regressor

Development Tools: Google Colab, GitHub
