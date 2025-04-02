House Rental Prediction using Machine Learning

📌 Project Overview

House rental prediction is a machine learning project that estimates rental prices based on various factors such as location, number of rooms, square footage, amenities, and market trends. This project leverages data-driven techniques to provide accurate rental price predictions.

🛠️ Technologies Used

Python

Flask (Web Framework)

NumPy, Pandas (Data Processing)

Scikit-Learn (Machine Learning)

Pickle (Model Serialization)

HTML, CSS (Frontend)

Git & GitHub (Version Control)

📂 Dataset

The dataset contains historical rental data, including:

Location (City, Zip Code, Neighborhood)

Property Size (Square Feet)

Number of Bedrooms & Bathrooms

Year Built

Rental Price (Target Variable)

📊 Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling and transformation

Splitting data into training and testing sets

🚀 Model Development

We experimented with different machine learning models such as:

Linear Regression

Random Forest Regressor

Gradient Boosting

Support Vector Machine (SVM)

Neural Networks (Optional)

Performance was evaluated using metrics like R² Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

🌐 Application Structure

Flask App (app.py): Handles user requests and serves predictions.

Model (model.pkl): Serialized trained model loaded for predictions.

Templates (index.html): Frontend user interface for input and results.

📌 How to Run the Project

1:Clone this repository:

git clone https://github.com/your-username/house-rental-prediction.git
cd house-rental-prediction

2:Install dependencies:

pip install -r requirements.txt

3:Run the application:

python app.py

4:Open http://127.0.0.1:5000/ in your browser to use the web app.
