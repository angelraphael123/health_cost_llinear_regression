# health_cost_linear_regression

This project uses a **neural network** to predict health insurance costs based on various input features, including demographic and lifestyle data. The model is built and trained using **TensorFlow** and **Keras**, leveraging the **insurance.csv** dataset.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results](#results)
- [License](#license)

---

## Project Overview

The goal of this project is to predict health insurance expenses using features such as:
- Age
- Gender
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Geographic region

The project implements a regression model using TensorFlow/Keras to predict a continuous target variable (`expenses`).

---

## Features
- Preprocessing categorical data using label encoding.
- Splitting the dataset into training and testing sets.
- Building a neural network regression model with TensorFlow/Keras.
- Visualizing model performance and loss during training.

---

## Dataset

### Source
The dataset is sourced from [FreeCodeCamp](https://cdn.freecodecamp.org/project-data/health-costs/insurance.csv).

### Columns:
1. **age**: Age of the policyholder.
2. **sex**: Gender of the policyholder (`male`, `female`).
3. **bmi**: Body Mass Index (BMI) of the policyholder.
4. **children**: Number of children covered under the policyholder's health insurance.
5. **smoker**: Smoking status (`yes`, `no`).
6. **region**: Geographic region (`northeast`, `southeast`, `southwest`, `northwest`).
7. **expenses**: Medical costs billed to the insurance company.

---

## Technologies Used
- Python
- TensorFlow 2.x
- Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/health-insurance-cost-prediction.git
   cd health-insurance-cost-prediction

---

## **Results**

Model Performance:
- The model was trained and evaluated using Mean Squared Error (MSE) as the loss function.
- Performance metrics and loss curves are plotted during training.
  
| Feature | Value       | Predicted Expenses | Actual Expenses |
| ------- | ----------- | ------------------ | --------------- |
| Age: 30 | Smoker: No  | \$3,450            | \$3,600         |
| Age: 45 | Smoker: Yes | \$25,000           | \$24,750        |

---

## **License**
This project is licensed under the MIT License.
