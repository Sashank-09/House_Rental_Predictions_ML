House Rental Prediction using Machine Learning

📌 Project Overview

House rental prediction is a machine learning project that estimates rental prices based on various factors such as location, number of rooms, square footage, amenities, and market trends. This project leverages data-driven techniques to provide accurate rental price predictions.

🛠️ Technologies Used

1.Python

2.Flask (Web Framework)

3.NumPy, Pandas (Data Processing)

4.Scikit-Learn (Machine Learning)

5.Pickle (Model Serialization)

6.HTML, CSS (Frontend)

7.Git & GitHub (Version Control)

📂 Dataset

The dataset contains historical rental data, including:

1.Location (City, Zip Code, Neighborhood)

2.Property Size (Square Feet)

3.Number of Bedrooms & Bathrooms

4.Year Built

5.Rental Price (Target Variable)

📊 Data Preprocessing

1.Handling missing values

2.Encoding categorical variables

3.Feature scaling and transformation

4.Splitting data into training and testing sets

🚀 Model Development

We experimented with different machine learning models such as:

1.Linear Regression

2.Random Forest Regressor

3.Gradient Boosting

4.Support Vector Machine (SVM)

5.Neural Networks (Optional)

Performance was evaluated using metrics like R² Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

🌐 Application Structure

1.Flask App (app.py): Handles user requests and serves predictions.

2.Model (model.pkl): Serialized trained model loaded for predictions.

3.Templates (index.html): Frontend user interface for input and results.

📌 How to Run the Project

1:Clone this repository:

git clone https://github.com/your-username/house-rental-prediction.git
cd house-rental-prediction

2:Install dependencies:

pip install -r requirements.txt

3:Run the application:

python app.py

4:Open http://127.0.0.1:5000/ in your browser to use the web app.
