# myapp
A Machine Learning web application that predicts the species of an Iris flower based on its sepal and petal measurements. The application is built using Python, Streamlit, and Scikit-Learn, with a Random Forest Classifier for prediction.

# Iris Flower Species Classifier using Streamlit

A **Machine Learning web application** that predicts the species of an Iris flower based on its sepal and petal measurements. The application is built using **Python, Streamlit, and Scikit-Learn**, with a **Random Forest Classifier** for prediction.

## Project Overview

This project demonstrates how a machine learning classification model can be integrated into an interactive web application using Streamlit.

Users can enter four flower measurements:

*  Sepal Length
*  Sepal Width
*  Petal Length
*  Petal Width

The trained Random Forest model predicts the Iris species and displays the **prediction confidence** for each possible class.

## Machine Learning Model

The project uses the built-in **Iris dataset** from Scikit-Learn.

**Algorithm:** Random Forest Classifier
**Dataset:** Iris Dataset
**Train-Test Split:** 80% Training / 20% Testing
**Evaluation:** Model Accuracy
**Prediction:** Iris Setosa, Iris Versicolor, or Iris Virginica

## Technologies Used

* Python
* Streamlit
* Scikit-Learn
* Random Forest
* Machine Learning
* Git & GitHub

## Features

* Interactive Streamlit web interface
* User-friendly input fields
* Real-time Iris species prediction
* Model accuracy display
* Prediction confidence/probability
* Simple and clean UI

## Project Structure

```text
Iris-Flower-Classifier/
│
├── app.py
├── README.md
└── requirements.txt
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/iris-flower-classifier.git
```

### 2. Navigate to the project folder

```bash
cd iris-flower-classifier
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser.

## Requirements

Create a `requirements.txt` file containing:

```text
streamlit
scikit-learn
```

## Learning Objectives

This project helps demonstrate:

* Loading datasets using Scikit-Learn
* Splitting data into training and testing sets
* Training a Random Forest classification model
* Evaluating model accuracy
* Making predictions on new data
* Using prediction probabilities
* Building an interactive ML application with Streamlit

## Author
**Keerthi M**
MSc Data Science and Analytics

