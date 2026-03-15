# Car Price Prediction System (TensorFlow)

This project implements a **car price prediction system** using TensorFlow.  
The model predicts the **price of a car** based on several vehicle features.

---

## Project Objective

The goal of this project is to build a **machine learning regression model** that can estimate car prices using vehicle characteristics.

The features used in the dataset include:

- Model year
- Mileage (km)
- Engine size
- Horsepower
- Vehicle age

The target variable is:

- **Car price**

---

##  Machine Learning Approach

This problem is treated as a **regression task** because the output is a **continuous numerical value (price)**.

The project covers the following TensorFlow concepts:

- Data preparation
- Train / Test split
- Model creation using **Sequential API**
- Model training
- Model evaluation
- Price prediction for new vehicles

---

##  Technologies Used

- Python
- NumPy
- Pandas
- TensorFlow / Keras
- Scikit-learn

---

##  Model Architecture

The neural network consists of:

- Input layer (car features)
- 2 hidden Dense layers with ReLU activation
- 1 output layer for price prediction

Loss Function:
