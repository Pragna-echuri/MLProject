# Student Performance Prediction

This project predicts a student's Math score based on their demographics, parental education, test preparation, writing score and reading score. It is built using Flask for the web interface and Scikit-Learn for the machine learning model.

## Objective 
The objective of this project is to develop a predictive model that estimates a student's Math score based on various factors such as demographics, parental education, test preparation, writing score, and reading score. By leveraging machine learning techniques, this project aims to:
- Provide students with an estimate of their expected math performance.
- Help educators identify students who may need additional academic support.
- Analyze the impact of different factors on a student's math performance.
- Demonstrate the practical application of Flask and Scikit-Learn in a web-based machine learning project.

### Machine Learning Model
- This project uses a regression model to predict a student's Math score. The model is trained using:
- Independent Variables: Gender, parental education, test preparation, reading score, writing score.
- Target Variable: Math Score
- Model Used: Linear Regression (or another suitable regression model)

## Features
- User-friendly web application to input student details.
- Machine Learning model trained to predict math scores.
- Flask backend for handling user inputs and predictions.
- Interactive web interface using HTML and Bootstrap.
- Uses Scikit-Learn for regression-based score prediction.

## Tech Stack
- Backend: Python, Flask
- Machine Learning: Scikit-Learn, Pandas, NumPy
- Frontend: HTML, Bootstrap
- Deployment: Flask Development Server


## Installation and Setup

1. Clone the Repository
2. Create a Virtual Environment (Optional but Recommended)
3. Install Dependencies
```bash
pip install -r requirements.txt
```
4. Run the Flask Application
```bash
python app.py
```
5. Access the Web App

- Open http://127.0.0.1:5000/predictdata in your browser.
- Fill in the student details in the form.
- Click Predict to see the estimated Math score.


