
# Bangalore Restaurant Prediction System

# Overview

This repository contains code for a restaurant prediction system built using Python. The system utilizes a dataset related to restaurants in Bangalore for training various regression algorithms to predict factors such as footfall, revenue, etc. Additionally, a web-based application has been developed to provide an interface for users to interact with the prediction model.

# Features

1- Utilizes machine learning regression algorithms to predict restaurant-related metrics.

2- Web-based application for easy interaction with the prediction model.

3- Uses the Extra Tree Regressor algorithm for improved accuracy.

4- Developed using PyCharm IDE for efficient coding and debugging.

# Requirements
1- Python 3.x

2- Necessary Python libraries (specified in requirements.txt)

3- PyCharm IDE (optional, for development)

# Installation

1- Clone this repository to your local machine:

bash
Copy code
git clone <repository_url>

2-Install the required Python libraries:

Copy code
pip install -r requirements.txt
Usage
Training the Model

3- Navigate to the model_training directory:

bash
Copy code
cd model_training

4- Run the Python script to train the regression model:

Copy code
python train_model.py

This script will load the dataset, preprocess it, train the model using various regression algorithms including the Extra Tree Regressor, and save the trained model to disk.

# Running the Web Application

1- Navigate to the web_app directory:

bash
Copy code
cd web_app

2- Run the Flask application:

Copy code
python app.py

### This will start the Flask server. You can access the web application by navigating to http://localhost:5000 in your web browser.

# Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.
## Authors

- [@Umer Abbasi](https://www.github.com/umerabbasi658)

