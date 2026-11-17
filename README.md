# SLR_Model_Machine_Learning
# Weight Prediction Using Height

## Project Overview

This project is a Machine Learning web application that predicts a person's weight based on their height using **Simple Linear Regression**.

The model is trained using a dataset containing height and weight values. A user can enter their height through a web interface, and the application predicts the estimated weight.

## Technologies Used

- **Python** – Programming language
- **Flask** – Web application framework
- **NumPy** – Numerical operations
- **Pandas** – Data handling and preprocessing
- **Scikit-learn** – Machine Learning model
- **HTML & CSS** – Frontend design
- **Pickle** – Saving and loading the trained model
- **PyCharm** – Development environment

## Machine Learning Algorithm

**Simple Linear Regression**

Simple Linear Regression is a supervised machine learning algorithm that identifies the relationship between one independent variable and one dependent variable.

In this project:

- Independent Variable (X): Height
- Dependent Variable (Y): Weight

The model learns the relationship between height and weight and uses it to predict weight for a given height.

## Project Structure

```text
MLProject/
│
├── Templates/
│   └── index.html
│
├── app.py
├── SLR_Model.pkl
├── requirements.txt
└── README.md
```


## How It Works

1. The user opens the web application.
2. The user enters their height.
3. The application receives the input through a Flask form.
4. The saved Linear Regression model processes the input.
5. The predicted weight is displayed on the webpage.

## Model Evaluation

The trained model can be evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) Score

These metrics help evaluate the model's prediction performance.

## Important Note

The predicted weight is an estimate based on the training dataset. It is intended for educational and demonstration purposes only and should not be considered a medical assessment.
