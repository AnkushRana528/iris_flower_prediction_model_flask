🌸 Iris Flower Prediction Web App (Flask + Decision Tree)

An end-to-end Machine Learning web application that predicts the species of an Iris flower based on input measurements.
The project demonstrates the complete ML workflow — from model training to deployment using Flask.

🚀 Project Overview

This application uses a Decision Tree Classifier trained on the Iris dataset to predict the flower category:

Iris-setosa

Iris-versicolor

Iris-virginica

Users can input flower measurements through a web interface, and the model returns predictions in real time.

🧠 Machine Learning Details

Algorithm: Decision Tree Classifier

Library: Scikit-learn

Dataset: Iris Dataset

Features Used:

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

The model was trained using a Pandas DataFrame and saved using pickle for deployment.

🛠 Tech Stack

Programming Language: Python

ML Library: Scikit-learn

Web Framework: Flask

Data Handling: Pandas, NumPy

Frontend: HTML, CSS

Version Control: Git & GitHub

✨ Features

Clean and user-friendly web interface

Real-time prediction using ML model

Flask-based backend integration

Virtual environment for dependency management

End-to-end ML deployment

GitHub-hosted project (portfolio-ready)

📁 Project Structure
iris_flower_prediction_model_flask/
│
├── deploy.py
├── savemodel.sav
├── Iris.csv
├── requirements.txt
│
├── templates/
│   └── index.html
│
└── README.md

▶️ How to Run the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/AnkushRana528/iris_flower_prediction_model_flask.git
cd iris_flower_prediction_model_flask
2️⃣ Create & Activate Virtual Environment
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Flask App
python deploy.py

📌 Learning Outcomes

Hands-on experience with Decision Tree classification

Understanding real-world ML deployment challenges

Feature consistency between training and inference

Backend–frontend integration using Flask

Version control and GitHub project management

🔮 Future Improvements

Deploy the app publicly (Render / Railway)

Add support for multiple ML models

Improve UI responsiveness

Add model performance metrics

Convert into a REST API

👤 Author

Ankush Rana
B.Sc. Artificial Intelligence & Machine Learning Student
Aspiring AI/ML Engineer

🔗 GitHub: https://github.com/AnkushRana528

⭐ If you like this project

Give it a ⭐ on GitHub — it motivates me to build more projects!
