# Bangalore Home Prices Prediction

This project demonstrates a step-by-step process to build a real estate price prediction website using machine learning. The application predicts home prices in Bangalore based on various features such as area, number of bedrooms, etc. The project involves three main components: model building, backend server, and frontend website.

## Project Components

1. **Model Building**:
    - Load and clean the dataset.
    - Perform outlier detection and removal.
    - Feature engineering and dimensionality reduction.
    - Model building using Scikit-learn and Linear Regression.
    - Hyperparameter tuning using GridSearchCV.
    - Model evaluation using K-fold cross-validation.

2. **Backend Server**:
    - Create a Python Flask server to serve HTTP requests.
    - Use the trained model to respond with predicted home prices.

3. **Frontend Website**:
    - Develop a user interface with HTML, CSS, and JavaScript.
    - Allow users to input home features (e.g., square footage, number of bedrooms).
    - Communicate with the Flask server to retrieve and display the predicted price.

## Technologies and Tools

- Python
- Numpy and Pandas for data cleaning
- Matplotlib for data visualization
- Scikit-learn for model building
- Jupyter Notebook, Visual Studio Code, and PyCharm as IDEs
- Python Flask for the HTTP server
- HTML/CSS/JavaScript for the frontend
- AWS EC2 for cloud deployment
- Nginx for web server
